---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/scripting-and-development/create-a-plugin-with-python-and-qml.html"
breadcrumb-title: ''
description: Substance 3D Sampler용 Python 및 QML을 사용하여 플러그인을 만들어 사용자 정의 사용자 인터페이스를 빌드하고 기능을 확장하는 방법을 알아봅니다.
helpx_creative_field: ""
helpx_description: Sampler > Scripting and Development > Create a Plugin with Python and QML
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Python 및 QML로 플러그인 만들기
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '729'
ht-degree: 0%

---


# Python 및 QML로 플러그인 만들기

이 안내서에서는 Python 및 QML을 사용하여 간단한 자동 저장 플러그인을 만드는 방법에 대해 설명합니다.

## 플러그인 구조

Sampler 플러그인을 가져오려면 적어도 Python 및 QML 파일이 필요하지만 플러그인 패널의 아이콘에 사용되는 이미지 등 다른 파일도 포함할 수 있습니다. 아래 예제에는 3개의 파일이 있습니다.

* **autosave.py**&#x200B;에는 플러그인의 논리가 포함되며 작동 방식을 결정합니다.
* **autosave.qml**&#x200B;은 Sampler에서 플러그인의 모양을 정의합니다.
* **autosave.svg**&#x200B;는 플러그인의 아이콘으로 사용되는 벡터 그래픽입니다.

플러그인에 필요한 파일이 단일 폴더에 있는 경우 편집 > 환경 설정 > 플러그인 및 스크립트를 통해 Sampler에 플러그인을 추가할 수 있습니다. 플러그인 관리에 대해 자세히 알아보려면 [여기](manage-installed-plugins-and-scripts.md)로 이동하세요.

## Python

아래 코드는 자동 저장 플러그인의 전체 python 파일입니다. 아래는 코드가 수행하는 작업에 대한 간략한 설명입니다. 그러나 코드에는 추가 정보가 있는 주석도 포함됩니다.

1. 관련 모듈을 가져옵니다.
   1. Qt는 멀티플랫폼 GUI 툴킷입니다. QtcCore, QtQml 및 QtQuick는 autosave.py와 autosave.qml 간의 통신에 사용하는 모듈입니다.
1. X분마다 프로젝트를 저장하는 **save()** 메서드를 정의합니다.
1. 자동 저장 클래스를 만듭니다. 이 클래스는 매개 변수가 플러그인의 동작을 변경할 수 있도록 **save()** 메서드가 플러그인 UI에 연결하는 방법을 지정합니다
1. 플러그인에 대한 설정을 수행하는 **register\_qml\_type()** 메서드를 정의합니다.
1. Sampler 내에서 플러그인을 호출합니다.

### autosave.py

```
## Import QT & QML modules to create the UI

from PySide2 import QtCore, QtQml, QtQuick 

## Import Sampler API

import substance_sampler as ssa 

## Import other modules for this specific example

import datetime 

import os 

import threading 

 

 

## Save the project every X minutes

def save(interval): 

    global t 

    ssa.save_project() 

    if ssa.save_project(): 

        now = datetime.datetime.now() 

        print("Autosave: %d:%d:%d" % (now.hour, now.minute, now.second)) 

    t = threading.Timer(interval, save, [interval]) 

    t.start() 

 

 

t = None 

 

 

## Declare the API AutoSave

class AutoSave(QtQuick.QQuickItem): 

    def __init__(self, parent=None): 

        super(AutoSave, self).__init__(parent) 

 

## Declare a first API function

## This function can be called from the QML file

## with 2 arguments, one string and one integer

    @QtCore.Slot(str, int) 

    def start_auto_save(self, default_path, interval): 

        if not ssa.save_project(): 

            ssa.save_project_as(os.path.join(default_path, "autosave.ssa")) 

        global t 

        t = threading.Timer(10, save, [interval]) 

        t.start() 

        print("Launch Autosave") 

 

## Second function of the API

## With no argument

    @QtCore.Slot(None) 

    def stop_auto_save(self): 

        global t 

        t.cancel() 

        print("Stop Autosave") 

 

 

## Function to declare the API and the panel

## First argument is Python class of your API

## Second argument is name of the API you will use in the QML file

## Third and fourth is the API version. In this case, 1.0

## Last is the name of the panel in Sampler UI

def register_qml_type(): 

    QtQml.qmlRegisterType(AutoSave, "AutoSave", 1, 0, "AutoSave") 

 

 

## Execute the plugin in Sampler UI thread

ssa.run_in_main_thread(register_qml_type)
```


## QML

QML 파일은 플러그인의 UI를 정의합니다. QML은 Qt 마크업 언어를 의미하며 HTML, XML 등 다른 마크업 언어와 유사하게 작동합니다. QML에 대한 자세한 내용은 [여기](https://doc.qt.io/qt-6/qmlapplications.html#:~:text=QML%20is%20a%20user%20interface%20specification%20and%20programming,imperative%20JavaScript%20expressions%20combined%20with%20dynamic%20property%20bindings.)에서 확인할 수 있습니다.

autosave.qml의 일반적인 구조는 다음과 같습니다.

1. 모듈을 가져옵니다.
   1. 가져온 Qt 모듈은 파일에 사용된 UI 요소에 필요합니다.
   1. **autosave.py**&#x200B;에서 만든 Autosave API 클래스도 가져왔습니다. QML 파일은 20행에서 이 클래스를 참조합니다.
1. 추적해야 하는 변수를 만듭니다.
   1. **autoSaveFolder**&#x200B;은(는) Sampler 파일이 자동 저장되는 폴더입니다.
   1. **timing**&#x200B;은 자동 저장 사이의 시간(초)입니다.
   1. **textColor**&#x200B;을(를) 사용하여 플러그인 UI의 텍스트 색상을 한 곳에서 업데이트할 수 있습니다.
1. Python API 인스턴스화
1. UI 정의.
   1. 여기에는 **autosave.py**&#x200B;에서 만든 python API에 대한 후크가 포함됩니다. 예:
      1. 47행에서는 &quot;Autosave every (min):&quot; 요소가 변경될 때마다 QML 파일 내의 **timing** 변수 값을 업데이트합니다.
      1. 64행은 API에서 **start\_auto\_save** 함수를 호출하고 **timing** 및 **autoSaveFolder** 변수를 매개 변수로 전달합니다.
1. 기본 파일 경로를 정리하는 방법을 만듭니다.

### autosave.qml

```
/* 

Import Qt modules to design the UI 

https://doc.qt.io/qt-5/qtqml-syntax-basics.html 

*/ 

import QtQuick 2.15 

import QtQuick.Controls 2.15 

import Qt.labs.platform 1.1 

import AutoSave 1.0 // Import API defined in the Python file 

 

Rectangle { 

  id: root 

  anchors.fill: parent 

  color: "#333333" 

 

  property var autoSaveFolder: removeQmlFilePathPrefix(StandardPaths.writableLocation(StandardPaths.DocumentsLocation)) 

  property var timing: 300 

  property var textColor: "#b3b3b3" 

 

  AutoSave { 

      id: api // Instantiate the Python API 

  } 

 

  Column { 

    id: controls 

    anchors.top: parent.top + 10 

    anchors.left: parent.left + 10 

    anchors.right: parent.right 

    width: parent.width 

    spacing: 20 

    leftPadding: 10 

    topPadding: 10 

 

    Column { 

        spacing: 5 

        Text { 

            id: timingTitle 

            text: "Autosave every (min): " 

            color: root.textColor 

        } 

        SpinBox { 

            id: timingControl 

            from: 1 

            to: 10 

            stepSize: 1 

            value: 5 

 

            onValueModified: ()=>{ 

                root.timing = timingControl.value * 60 

            } 

        } 

    } 

    Row { 

        Text { 

            text: "Off" 

            color: root.textColor 

            anchors.verticalCenter: toggle.verticalCenter 

        } 

        Switch { 

            id: toggle 

            checked: false 

 

            onClicked: ()=>{ 

                if (checked === true) { 

                    api.start_auto_save(root.autoSaveFolder, root.timing) // Call a function of the API with 2 arguments 

                } 

                else if (checked === false) { 

                    api.stop_auto_save() // Call a function of the API 

                } 

            } 

        } 

        Text { 

            text: "On" 

            color: root.textColor 

            anchors.verticalCenter: toggle.verticalCenter 

        } 

 

    } 

    Column { 

        spacing: 5 

        Text { 

            text: "Default Autosave Path" 

            color: root.textColor 

            } 

        Row { 

            id: folderInput 

            TextField { 

                id: folderText 

                text: root.autoSaveFolder 

                readOnly: true 

            } 

            Button { 

                id: folderSelection 

                text: qsTr("...") 

                width: 40 

                onClicked: ()=>{ 

                    folderDialog.open() 

                    } 

            } 

        } 

    } 

 

    FolderDialog { 

        id: folderDialog 

 

        onAccepted: ()=>{ 

            root.autoSaveFolder = removeQmlFilePathPrefix(folderDialog.currentFolder) 

        } 

    } 

 

  } 

      function qmlFilePathPrefix() { 

        if (Qt.platform.os === "windows") { 

            return "file:///" 

        } 

        return "file://" 

    } 

    function removeQmlFilePathPrefix(filePath) { 

        var prefix = qmlFilePathPrefix() 

        return filePath.toString().replace(prefix, '') 

    } 

}
```


## SVG

**autosave.svg**&#x200B;이(가) **autosave.py**&#x200B;나 **autosave.qml**&#x200B;에서 명시적으로 호출되거나 언급되지 않았음을 확인했을 수 있습니다. Sampler에서 PY 파일과 이름이 같은 SVG 파일을 찾아 자동으로 플러그인 아이콘으로 사용하기 때문입니다.

>[!NOTE]
>
> 플러그인 폴더에 플러그인의 PY 파일과 일치하지 않는 파일 이름을 가진 SVG이 포함되어 있으면 플러그인에 아이콘이 포함되지 않습니다. 이렇게 하면 Sampler UI에 플러그인이 표시되지 않은 모양이 만들어집니다. 이 경우 Sampler의 오른쪽 막대 위로 커서를 이동하여 플러그인을 강조 표시합니다.
> 
> 브라우저가 HTML5 비디오 요소를 지원하지 않습니다.

플러그인 폴더에 SVG 파일이 없으면 기본 플러그인 아이콘이 대신 사용됩니다.

다음은 위에서 만든 자동 저장 플러그인에 사용할 수 있는 예제 SVG입니다.

[autosave.svg](https://helpx.adobe.com/content/dam/help/en/substance-3d/documentation/sadoc/files/234455541/234455542/1/1662460696349/autosave.svg)

## 자동 저장 플러그인의 제한 사항

위에서 만든 자동 저장 플러그인이 작동하지만 완벽하지 않습니다. 예를 들어, 자동 저장이 활성화된 후에 자동 저장 간격을 조정해도 실제로 자동 저장 사이의 시간은 변경되지 않습니다. API로 전송할 UI의 값에 대해 자동 저장을 비활성화했다가 다시 활성화해야 합니다.

Python과 QML을 함께 사용하는 것이 처음이라면 이 버그를 수정하는 것은 플러그인의 서로 다른 부분이 서로 통신하는 방식을 이해하는 데 유용한 방법입니다.
