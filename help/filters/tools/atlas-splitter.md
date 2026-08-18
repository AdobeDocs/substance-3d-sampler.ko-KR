---
helpx_url: "https://helpx.adobe.com/kr/substance-3d-sampler/filters/tools/atlas-splitter.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 Atlas Splitter 툴을 사용하여 텍스처 아틀라스를 재질 편집을 위해 개별 텍스처 맵으로 분할합니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Atlas Splitter
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Atlas Splitter
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '441'
ht-degree: 0%

---


# Atlas Splitter

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-atlassplitter-18-n-d.png)

**내부:** 도구

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

**Atlas Splitter**&#x200B;은(는) 아틀라스의 요소를 구성하고 볼 수 있는 유용한 도구입니다.

아래 이미지는 작동 중인 **Atlas Splitter**&#x200B;을(를) 보여줍니다.

![](../../assets/3d-2d-filters-cropped-0039-atlas-splittter-in.jpg)

위 이미지는 레이어 스택에 추가된 아틀라스 재질을 보여줍니다. **Atlas Splitter**&#x200B;를 사용하여 지도에서 특정 요소를 선택합니다.

![](../../assets/3d-2d-filters-cropped-0038-atlas-splitter-out.jpg)

레이어 스택에 **Atlas Splitter**&#x200B;을 추가하면 잎사귀 하나 또는 아틀라스 재질의 다른 요소에 집중할 수 있습니다.

</td>
</tr>
</table>

## 매개변수

**기본 매개 변수**

* **격자 보기**: 토글\
  요소의 격자 보기와 개별 보기 간에 전환합니다. 활성화하면 다음과 같은 추가 매개변수가 나타납니다.
  * **격자 불투명도**: 0-1\
    격자 불투명도 수정
  * **격자 선택 불투명도**: 0-1\
    선택한 요소 주위의 테두리 불투명도 수정
  * **자동 크기 조정**: 토글\
    아틀라스 요소의 배율을 조정하여 각 격자 사각형을 채울지 여부를 전환합니다.
* **자동 자르기**: 전환\
  선택한 모양의 자르기를 조정할지 여부를 선택합니다. 활성화되면 추가 옵션이 표시됩니다.
  * **자동 자르기 모드**:\
    선택한 요소를 자르고 재료의 공간을 채우는 방법을 선택합니다.
* **모양 선택**: 1-10\
  선택된 아틀라스의 요소를 변경합니다. 요소가 10개를 초과하는 슬라이드의 경우 **모양 선택** 값에 숫자를 입력하여 슬라이더의 범위를 변경할 수 있습니다.
* **회전**: 0-1\
  요소 회전

**고급 매개 변수**

* **작은 모양 허용치**: 0-1\
  **Atlas Splitter**&#x200B;에서 선택할 모양의 최소 크기를 조정합니다. 아티팩트를 필터링하는 데 유용합니다
* **자동 회전**: 전환\
  활성화되면 요소가 유사한 방향을 갖도록 자동으로 회전됩니다.
* **불투명도 마스크 축소**: 0-4\
  불투명 마스크의 비율을 조정합니다. 이 값을 늘리면 불투명도 마스크의 품질이 낮아질 수 있습니다.
* **모양 검색 정밀도**:\
  사용할 모양 감지 알고리즘을 선택합니다.
* **확장 너비**: 0-32\
  확장 수정 - 요소 테두리의 색상을 마스크 영역으로 돌출시켜 아틀라스 요소 가장자리의 투명도 문제를 방지합니다. **2D 보기**&#x200B;에서 기본 색상 채널을 보고 결과를 확인하십시오.
* **사용자 지정 배경색**: 전환\
  활성화하면 일반 채널의 배경색을 수정하는 컨트롤이 표시됩니다.
  * **표준 배경색**: 색상 선택\
    재질의 투명한 부분에서 표준 채널의 사용자 정의 배경색을 선택합니다.
* **Height 배경색**: 0-1\
  Height 채널의 배경색을 조정합니다. 일반적으로 요소 테두리에 아티팩트가 나타나지 않도록 Height 배경이 아틀라스 요소 테두리의 평균 Height과 일치하도록 하는 것이 좋습니다.
