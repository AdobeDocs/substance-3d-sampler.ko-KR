---
helpx_url: "https://helpx.adobe.com/kr/substance-3d-sampler/technical-support/configuration/nvidia-driver-settings.html"
breadcrumb-title: ''
description: GPU 성능을 최적화하고 느린 동작을 해결하기 위해 Substance 3D Sampler에 대한 NVIDIA 드라이버 설정을 구성하는 방법에 대해 알아보십시오.
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Configuration > NVIDIA Driver Settings
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: NVIDIA 드라이버 설정
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '262'
ht-degree: 0%

---


# NVIDIA 드라이버 설정

NVIDIA GPU를 사용하고 있지만 성능이 부진한 경우에는 두 가지 일반적인 원인이 있습니다.

1. 드라이버가 없거나 최신 상태가 아님
1. Sampler에서 잘못된 GPU를 사용하고 있습니다.

## 드라이버 업데이트

NVIDIA 드라이버 업데이트 방법:

1. NVIDIA의 드라이버 다운로드 페이지로 이동 - <https://www.nvidia.com/Download/index.aspx?lang=en-us>
1. GPU 모델을 선택하고 드라이버를 다운로드합니다.
1. 다운로드한 파일과 함께 드라이버를 설치합니다.

최신 드라이버가 설치되면 Sampler을 열어 성능이 개선되었는지 확인합니다. 성능이 느린 경우 Sampler에서 잘못된 GPU를 사용하고 있을 수 있습니다.

## Sampler 구성

Sampler에서 사용 중인 GPU를 확인하려면 다음을 수행하십시오.

![](../../assets/nvidiacontrolpanel.png)

1. NVIDIA 제어판을 엽니다. NVIDIA 제어판을 열려면 다음 중 하나를 수행합니다.
   1. 시작 메뉴를 사용하여 NVIDIA 제어판 검색
   1. 시스템 트레이에서 Geforce 아이콘을 마우스 오른쪽 단추로 클릭하고 NVIDIA 제어판을 선택합니다.
1. NVIDIA 제어판의 왼쪽 메뉴에서 [3D 설정 관리]를 선택합니다.
1. 프로그램 설정 탭을 선택합니다.
1. 맞춤화할 프로그램 선택에서 드롭다운을 사용하여 Sampler을 찾습니다.
1. Sampler이 드롭다운에 나열되지 않은 경우 추가 를 사용합니다.
   1. Sampler의 설치 위치를 찾습니다(기본 설치 위치는 **C:/Program Files/Adobe/Adobe Substance 3D Sampler**&#x200B;입니다).
   1. 설치 위치에서 **Adobe Substance 3D Sampler.exe**&#x200B;를 선택합니다.
1. Sampler을 선택한 상태에서 &quot;이 프로그램에 사용할 그래픽 프로세서 선택:&quot;에서 &quot;고성능 NVIDIA 프로세서&quot;를 선택합니다.
1. [적용]을 클릭합니다.

이 프로세스를 따랐으면 Sampler을 열어 성능이 개선되었는지 확인하십시오.
