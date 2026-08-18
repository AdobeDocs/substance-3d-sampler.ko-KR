---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/adjustments/colorize.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 [색상화] 필터를 사용하여 색조와 단색 색상화 효과를 텍스처와 재질에 적용합니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Colorize
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 색상화
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '313'
ht-degree: 1%

---


# 색상화

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/S_ColorFill_18_N_D.png)

**인:** 조정

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

색상화 를 사용하면 디테일을 잃지 않고 선택한 채널에 색상을 추가할 수 있습니다.

>[!NOTE]
>
> [색상화] 필터를 사용하여 일반 채널을 수정할 수 있지만 일반 채널의 작동 원리와 재질에 미치는 영향을 제대로 이해하고 있지 않은 경우에는 수정할 수 없습니다. 이는 일반적으로 특정 상황에서만 필요해야 하는 고급 기능이다.

이 이미지에서는 **색상화 필터**&#x200B;를 사용하여 기본 색상을 조정하여 훨씬 풍부한 나무 재질을 만들었습니다.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0045-colorize-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0044-colorize-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## 매개변수

**기본 매개 변수**

이 섹션에서 사용할 수 있는 매개 변수는 **채널 선택**&#x200B;을 기준으로 변경됩니다.

* **채널 선택**:\
  필터가 영향을 미치는 채널을 선택합니다. 선택한 채널을 2D 보기에서 보고 필터 결과를 직접 보는 것이 좋습니다.
  * ***기본 색상/발광 옵션***
    * ***채널 이름*** **- 색상**: 색상 선택\
      채널 색상을 지정하는 데 사용할 색상 선택
    * ***채널 이름*** **- 광도 유지**: 전환\
      이 옵션을 활성화하면 원래 색상의 밝기 또는 광도 값이 유지됩니다
    * ***채널 이름*** **- 강도**: 0-1\
      [색상화] 효과의 강도를 조정합니다.
  * ***일반 채널 옵션***
    * **표준 - 경사 각도**: 0-90\
      표준의 그레이디언트 수정
    * **표준 - 방향**: 0-360\
      법선 방향의 조정
    * **표준 - 광도 유지**: 전환\
      이 옵션을 활성화하면 원래 표준의 광도가 유지됩니다
    * **표준 - 강도**: 0-1\
      [색상화] 효과의 강도를 조정합니다.
* **사용자 지정 마스크**: 토글\
  사용자 정의 마스크 사용을 활성화하거나 비활성화합니다. 활성화하면 다음 매개변수가 나타납니다.
  * **마스크**: 이미지/브러시\
    마스크로 사용할 이미지를 선택하거나 브러시를 사용하여 2D 보기에서 직접 사용자 정의 마스크를 칠합니다
  * **사용자 지정 마스크 - 흐림 효과**: 0-1\
    마스크에 흐림 효과 적용
  * **사용자 지정 마스크 - 반전**: 전환\
    마스크 반전
