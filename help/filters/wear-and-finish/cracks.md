---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/cracks.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 균열 필터를 사용하여 사실적인 균열 패턴과 재료의 표면 손상 효과를 추가하십시오.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Cracks
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 균열
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '299'
ht-degree: 1%

---


# 균열

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-cracks-18-n-d.png)

**내부:** 마모 및 완료

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

**균열 필터**&#x200B;를 사용하여 균열과 틈새 네트워크를 추가하여 자료를 노화하고 손상시킵니다.

**균열 필터**&#x200B;가 깨끗한 대리석 재질에 적용되었습니다.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0043-cracks-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0042-cracks-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## 매개변수

**기본 매개 변수**

* **임의화**:\
  임의식은 이 필터에서 임의성을 사용하는 다른 매개 변수의 임의값을 결정합니다.
* **균열 스프레드**: 0-1\
  균열이 확산되는 정도를 조정합니다. 이렇게 하면 균열 너비와 길이가 모두 수정됩니다.
* **균열 양**: 0-1\
  표시할 균열 수를 변경합니다.

**마스크**

* **사용자 지정 마스크 사용**: 전환\
  사용자 정의 마스크 사용을 활성화하거나 비활성화합니다. 활성화하면 다음 매개변수가 나타납니다.
  * **마스크**: 이미지/브러시\
    마스크로 사용할 이미지를 선택하거나 브러시를 사용하여 2D 보기에서 직접 사용자 정의 마스크를 칠합니다.
  * **사용자 지정 마스크 - 반전**: 전환\
    마스크를 반전합니다.

**균열**

* **균열 색상**: 색상 선택\
  균열으로 표시되는 내부 표면의 색상을 변경합니다.
* **균열 거칠음**: 0-1\
  균열의 거칠기 값을 조정합니다.
* **균열 거칠음 불투명도**: 0-1\
  **균열 거칠기** 값이 거칠기 맵에 영향을 주는 정도를 조정합니다.
* **균열 금속**: 0-1\
  균열의 금속 값을 수정합니다.
* **균열 금속 불투명도**: 0-1\
  **균열 금속** 값이 금속 맵에 미치는 영향 조정
* **균열 Height 강도**: 0-1\
  균열 깊이 조정 이는 필터의 Height 맵과 표준 맵 결과 모두에 영향을 줍니다.

**고급 매개 변수**

* **표준 강도**: 0-1\
  균열 표준의 강도를 조정합니다.
* **Height 범위**: 0-1\
  전체 재질의 Height 범위를 수정합니다. 균열의 Height을 조정하려면 **균열 > 균열 Height 강도**&#x200B;를 사용하세요.
* **Height 위치**: 0-1\
  전체 재질의 Height 맵을 오프셋합니다.
