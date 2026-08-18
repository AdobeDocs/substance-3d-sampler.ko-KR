---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/scripting-and-development/create-a-script-with-python.html"
breadcrumb-title: ''
description: Substance 3D Sampler에서 Python 스크립트를 만들어 워크플로우를 자동화하고 애플리케이션 기능을 확장하는 방법을 알아봅니다.
helpx_creative_field: ""
helpx_description: Sampler > Scripting and Development > Create a Script with Python
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Python으로 스크립트 만들기
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '189'
ht-degree: 0%

---


# Python으로 스크립트 만들기

이 안내서에서는 Python을 사용하여 간단한 자동 저장 플러그인을 만드는 방법에 대해 설명합니다.

## 스크립트 구조

스크립트를 Sampler으로 가져오려면 단일 PY 파일이 필요합니다. 아래의 예제 스크립트를 PY 파일로 저장하고 Sampler으로 가져올 수 있습니다.

## 예제 스크립트

아래 스크립트는 재질의 각 레이어에 대해 새 임의 시드를 선택하여 재질의 변형을 자동으로 만듭니다. 이 기능은 재료가 특정 임의의 시드에 의존하는 대신 일반적인 경우에 사용할 수 있도록 하는 데 유용합니다.

### random\_seed\_variations.py

```
import substance_sampler as ssa 

from random import randrange 

 

## Get the current asset loaded in the layer stack

my_asset = ssa.get_selected_asset() 

 

## Create a list of all layers of the current asset

my_asset_layers = my_asset.get_layers() 

 

## Go through the layers list

for layer in my_asset_layers: 

## Go through all parameters of each layer

    for parameter in layer.parameters: 

## if the parameter is Random Seed, change is value

        if parameter.label == "$randomseed": 

            parameter.value = randrange(10000) 

            print(f"Random Seed for layer {layer.name}: {parameter.value}") 

 
```


위 코드에는 각 줄에서 일어나는 일을 설명하는 주석이 포함되어 있습니다.

## 스크립트 가져오기

위의 스크립트를 컴퓨터에 PY 파일로 저장한 후 편집 > 환경 설정 > 플러그인 및 스크립트를 사용하여 가져올 수 있습니다. 가져오면 **스크립트** 옵션이 **파일** 및 **편집**&#x200B;과 함께 메뉴 표시줄에 나타납니다. 여기에서 스크립트를 실행할 수 있습니다.

스크립트 관리에 대한 자세한 내용은 [여기](../manage-installed-plugins-and-scripts.md)에서 확인할 수 있습니다.
