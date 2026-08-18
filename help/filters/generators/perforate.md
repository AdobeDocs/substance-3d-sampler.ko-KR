---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/perforate.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 천공 생성기를 사용하여 재질과 텍스처에 천공된 패턴과 구멍 배열을 만들 수 있습니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Perforate
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 구멍
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '453'
ht-degree: 0%

---


# 구멍

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-perforation-18-n-d.png)

**내부:** 생성기

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

천공 필터를 사용하여 재질에 구멍을 추가합니다.

***천공 필터**를 적용하기 전과 적용한 후*

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0007-perforate-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0006-perforate-out.jpg){width="200px"}

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
* **패턴 선택**:\
  구멍의 모양을 선택하거나 [사용자 정의 패턴]을 선택하여 구멍을 직접 만듭니다.
* **천공 위치**:\
  표준과 Height이 재질 안으로 오목하게 들어가거나 재질에서 돋보이도록 할지 선택합니다
* **천공 모접기 크기**: 0-1\
  구멍의 모서리에서 모따기 크기 변경
* **구멍 크기**: 0-1\
  구멍의 크기 변경
* **마스크 사용**: 전환\
  브러시 또는 이미지로 천공을 마스킹하는 데 사용할 수 있는 **마스크 섹션**&#x200B;을(를) 활성화합니다.
* **비율 맵 사용**: 토글\
  비율 맵을 사용할 수 있습니다. 이 옵션을 활성화하면 다음 매개변수가 나타납니다.
  * **맵 배율**: 0-1\
    눈금 맵이 천공의 눈금에 미치는 영향을 조정합니다.
  * **비율 맵 반전**: 전환\
    비율 맵 값 반전
  * **사용자 지정 크기 맵**: 이미지/브러시\
    비율 맵으로 사용할 이미지를 가져오거나 브러시를 사용하여 **2D** **보기**&#x200B;에서 비율 맵을 직접 페인트합니다.

**마스크**

이 섹션은 **기본 매개 변수 > 마스크 사용**&#x200B;이 활성화된 경우에만 표시됩니다.

* **마스크 반전**:
* **마스크 흐림 효과**: 0-1\
  마스크에 적용된 흐림 효과 조정
* **마스크 임계값**: 0-1\
  마스크의 임계값을 수정합니다. **마스크 흐림 효과** 및 **마스크 임계값** 값을 함께 사용하여 마스크의 가장자리를 세밀하게 조정합니다.
* **사용자 지정 마스크**: 이미지/브러시\
  마스크로 사용할 이미지를 가져오거나 **2D 보기**&#x200B;에서 직접 자신의 마스크를 페인팅합니다.

**천공**

* **천공 크기**: 0-1\
  구멍과 모따기를 포함하는 각 구멍의 크기를 변경합니다.
* **천공 Y 양**: 1-64\
  Y축의 천공 수 조정
* **천공 X 양**: 1-64\
  X축의 천공 수 조정
* **천공 밀도**: 0-1\
  무작위로 천공 마스크
* **천공 오프셋**: 0-1\
  두 번째 구멍 행마다 오프셋 조정
* **천공 색상 불투명도**: 0-1\
  구멍의 모따기 영역 색상의 투명도 조정
* **천공 색상**: 색상 선택\
  각 천공의 모따기 영역 색상을 선택합니다
* **천공 거칠음**: 0-1\
  구멍의 거칠음 값 수정
* **천공 금속**: 0-1\
  구멍의 금속 값 수정

**고급 매개 변수**

* **광도**: 0-1
* **대비**: -1 대 1
* **색조 이동**: 0-1
* **채도**: 0-1
* **표준 강도**: -1 ~ 1\
  각 천공의 수직 강도 조정
* **Height 강도**: 0-1\
  각 천공 Height 맵의 강도 조정
