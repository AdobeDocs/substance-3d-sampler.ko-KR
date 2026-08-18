---
helpx_url: "https://helpx.adobe.com/kr/substance-3d-sampler/filters/tools/image-to-material.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 이미지로 재질 도구를 사용하여 AI 기반 처리를 사용하여 단일 이미지를 전체 PBR 재질로 변환합니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Image To Material
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 이미지를 재료로
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 1%

---


# 이미지를 재료로

![](../../assets/sat-icon-image-to-material.png)

**Image to Material** 템플릿을 사용하면 단일 입력 이미지에서 고품질 PBR 자료를 생성할 수 있습니다.

이 템플릿에는 두 가지 주요 알고리즘이 있습니다.

* **AI 기반**
* **B2M**

각 알고리즘에 대한 자세한 설명은 아래를 참조하십시오.

## 예

다음은 단일 입력 이미지에서 생성된 재질 채널의 예입니다.

![](../../assets/sat-image-to-material.jpg){width="500px"}

## 알고리즘

**이미지를 재질** 템플릿으로 변경하려면 템플릿 이름 아래의 드롭다운을 클릭합니다.

![](../../assets/image-to-material-algo-setting.png)

### AI 기반

<b>AI 기반</b> 알고리즘은 머신 러닝을 사용하여 모양과 개체를 인식하고 [표준], [Height] 및 [거칠음] 맵을 정확하게 생성하고 어두운 영역이나 밝은 영역에서 알베도를 제거합니다.

신경망은 직물, 유기, 실내 및 실외 표면과 같은 광범위한 재료들에 대해 훈련되어 왔다.

>[!NOTE]
>
> Image to Material(AI 기반)은 고해상도 이미지를 계산하는 데 시간이 더 오래 걸립니다. 작업하는 동안 워크플로우를 최적화하려면 [레이어 해상도](../../interface/preferences/layer-resolution.md) 시스템을 사용하는 것이 좋습니다.

### B2M

**B2M** 알고리즘은 Substance 기반의 비트맵 대 재질 방법을 사용하여 기본 색상, 보통, 금속, 거칠기 및 주변 오클루전과 같은 여러 채널을 절차 기술을 사용하여 생성합니다.

이 알고리즘은 덜 정확한 결과를 얻을 수 있지만 더 넓은 범위의 입력 이미지에 대해 작동합니다.

## Adobe Capture

이 기능은 Adobe Capture 모바일 앱(Android 및 iOS)에서도 사용할 수 있습니다. 장소에 상관없이 사진을 촬영하고, 스마트폰에서 바로 결과를 미리 볼 수 있습니다.

더 많은 버전을 위해 결과를 Substance 3D Sampler으로 손쉽게 보낼 수 있습니다.

![](../../assets/capture-qr-code.gif)

>[!NOTE]
>
> 이 기능은 Adobe Substance 3D Collection 구독에서만 사용할 수 있습니다.
