---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/multiangle-to-material.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 다중 각도를 자료로 툴을 사용하여 표면에 대한 여러 각도 사진으로 재질을 만들 수 있습니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Multiangle To Material
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 다중 각도를 자료로
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '276'
ht-degree: 0%

---


# 다중 각도를 자료로

![](../../assets/sat-multi-angle.png)

**다중 각도를 자료로** 템플릿은 특정 조명 조건에서 촬영한 2~8개의 입력 이미지를 재질로 만듭니다. 그러한 광 조건들은 재료 스캐너로 달성될 수 있다.

>[!NOTE]
>
> 이 문서[&#128279;](https://www.adobe.com/products/substance3d/magazine/your-smartphone-is-a-material-scanner-vol-ii.html)에서 자체 재질 스캐너를 만드는 방법에 대한 자세한 정보를 찾을 수 있습니다.

## 예

다음은 8개의 입력 이미지로 만든 재질의 예입니다.

* 처음 8개의 이미지는 8개의 광각에서 촬영된 스캔 이미지이다.
* 아래쪽 이미지는 템플릿(기본 색상, 표준, Height, 금속 및 거칠기)의 출력입니다.

![](../../assets/scan-801x697.jpg){width="400px"}

## Substance 3D Sampler 구성

PBR 채널이 올바르게 추출되도록 설정하고 구성할 세 가지 사항이 있습니다.

* 스캔 이미지 순서
* 첫 번째 입력 조명 각도
* 다음 입력 조명 각도

![](../../assets/multiangles-1024x1024.jpg){width="450px"}

### 이미지 스캔 순서

이미지를 가져올 때 이미지 가져오기 레이어에서 8개의 이미지가 연속적인지 확인합니다.

예를 들어 0°의 첫 번째 이미지는 **scan1**&#x200B;이어야 하고 45°의 이미지는 **scan2**&#x200B;이어야 합니다... 315°의 이미지는 **scan8**&#x200B;이어야 합니다.

![](../../assets/multiangle-image-import.png){width="450px"}

### 첫 번째 및 다음 광각

다중 각도를 자료로 레이어에서 다음 작업을 수행합니다.

* 첫 번째 입력 조명 각도를 설정합니다. **scan1**&#x200B;이 180°이면 첫 번째 입력 광각 =0.5이고, **scan1**&#x200B;이 0°이면 첫 번째 입력 광각 = 0입니다.
* 다음 입력 조명 각도 설정: 이미지의 회전 방향을 정의합니다. scan1이 0°이면 scan2는 45°입니다... 값은 **시계 반대 방향**&#x200B;입니다.

![](../../assets/multiangle-multiangle-to-material.png){width="450px"}
