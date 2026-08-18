---
helpx_url: "https://helpx.adobe.com/kr/substance-3d-sampler/technical-support/configuration/retrieving-the-installation-path.html"
breadcrumb-title: ''
description: 스크립팅 및 구성을 위해 여러 플랫폼에서 Substance 3D Sampler의 설치 경로를 검색하는 방법을 알아봅니다.
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Configuration > Retrieving the installation path
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 설치 경로 검색
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '259'
ht-degree: 5%

---


# 설치 경로 검색

이 페이지에서는 버전 및 플랫폼에 따라 애플리케이션의 설치 경로를 검색하는 방법에 대한 정보를 다시 그룹화합니다.

## Windows

### Creative Cloud 데스크톱

1. Windows 레지스트리 편집기(**regedit**)를 엽니다.
1. 레지스트리 키로 이동합니다. **&#x200B; HKEY\_LOCAL\_MACHINE\Software\Microsoft\Windows\CurrentVersion\App 경로\**
1. 이름이 **Adobe Substance 3D Sampler.exe**&#x200B;인 하위 키를 엽니다.
1. 키 값에는 키가 설치된 응용 프로그램 실행 파일의 경로가 포함됩니다

>[!NOTE]
>
> 이 레지스트리 키는 버전 3 이후에만 사용할 수 있습니다.\
> 이전 버전의 경우 **HKEY\_CURRENT\_USER\Software\Microsoft\Windows\CurrentVersion\ Explorer\FileExts**&#x200B;의 파일 연결에서 설치 경로를 검색할 수 있습니다.

### Substance 3D Standalone

1. Windows 레지스트리 편집기(**regedit**)를 엽니다.
1. 레지스트리 키로 이동합니다. **HKEY\_LOCAL\_MACHINE\ SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall**
1. 애플리케이션 버전의 AppID와 일치하는 하위 키를 찾습니다(아래 표 참조).
1. 키 값에는 응용 프로그램 설치 위치에 대한 경로가 포함됩니다

| 버전 | AppId |
| --- | --- |
| **1.x(2019.x) ~ 2.x** | {B3506E85-E98F-4D48-A010-BE4DEE27D108} |
| **3.x 이상** | {ED4A4ABC-9B7D-44B8-984A-C8A994B69CFD} |

### 증기

Steam 설치 폴더의 **steamapps/common/** 하위 폴더에 응용 프로그램이 설치되어 있습니다.

## Mac

Mac에서 애플리케이션은 다음 위치에 설치됩니다.

| 버전 | 경로 |
| --- | --- |
| **3.x 이상** | **/Applications/Adobe Substance 3D Sampler.app** |
| **레거시** | **/Applications/Substance Alchemist.app** |

## 리눅스

Linux에서 rpm 패키지는 다음 경로에 설치됩니다.

| 버전 | 경로 |
| --- | --- |
| **3.x 이상** | **/opt/Adobe/Adobe\_Substance\_3D\_Sampler** |
| **레거시** | **/opt/Allegorithmic/Substance\_Alchemist** |
