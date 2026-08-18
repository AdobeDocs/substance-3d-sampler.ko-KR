---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/decal.html"
breadcrumb-title: ''
description: Substance 3D Sampler에서 데칼 생성기를 사용하여 재료 서피스에 대한 데칼 패턴과 오버레이 텍스처를 생성합니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Decal
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 데칼
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '321'
ht-degree: 1%

---


# 데칼

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-decal-18-n-d.png)

**내부:** 생성기

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

데칼 필터를 사용하면 특정 위치에 다른 재질의 인스턴스를 추가할 수 있습니다. 이 기능은 절차적으로 생성하기 쉽지 않은 스티커나 특정 세부 사항과 같은 요소를 추가할 때 유용합니다.

아래 이미지는 콘크리트에 손상을 추가하는 데 사용되는 **데칼 필터**&#x200B;를 보여줍니다.

![](../../assets/3d-2d-filters-cropped-0045-decal-in.jpg)

데칼이 첨가되기 전에, 콘크리트 기층은 깨끗하고 손상되지 않았다.

![](../../assets/3d-2d-filters-cropped-0044-decal-out.jpg)

**데칼 필터**&#x200B;이(가) 적용되면 사실적인 균열과 손상이 재질에 추가됩니다.

</td>
</tr>
</table>

## 매개변수

**기본 매개 변수**

* **타일링 모드**:\
  **2D 보기**&#x200B;의 핸들을 넘어 바둑판식으로 표시할지 여부를 결정합니다.\
  H는 Horizontal을, V는 Vertical을 나타냅니다.
* **아래쪽 재질 색상 일치**: 0-1\
  데칼 재질의 색상을 그 아래 레이어의 색상 값과 일치하도록 조정합니다.
* **표준 혼합 모드**:\
  데칼 재질과 기본 레이어 간에 표준 색상이 혼합되는 방식을 조정합니다
* **표준 불투명도 혼합**: 0-1\
  데칼 재질 표준의 불투명도 변경
* **데칼 Height 위치**: 0-1\
  기본 레이어 Height을 기준으로 데칼의 Height 조정
* **데칼 Height 비율**: 0-1\
  데칼 재질의 Height 맵 대비 변경

**고급 매개 변수**

* **데칼 변환**:\
  데칼의 행렬 변형 값을 조정합니다. 일반적으로 데칼의 변환을 조정하려면 **2D 보기**&#x200B;의 핸들을 사용하는 것이 더 쉽습니다.
* **데칼** **오프셋**: -1 - 1\
  데칼의 오프셋을 조정합니다.

## 사용 안내서

데칼 필터를 사용하려면 다음을 수행하십시오.

1. 레이어 스택에 데칼 필터 추가
1. Decal 레이어 아래에 입력 슬롯이 나타납니다.
1. 데칼 재질을 데칼 레이어의 입력 슬롯으로 드래그합니다

데칼 레이어를 선택하여 **속성 패널**&#x200B;에서 필터 매개 변수를 조정할 수 있습니다.

입력 슬롯에서 재질을 선택하여 **속성 패널**&#x200B;에서 데칼 입력 자료의 매개 변수를 조정할 수 있습니다.
