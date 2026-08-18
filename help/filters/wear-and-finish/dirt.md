---
helpx_url: "https://helpx.adobe.com/kr/substance-3d-sampler/filters/wear-and-finish/dirt.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 Dirt 필터를 사용하여 실제 Dirt 축적과 그림 효과를 재질과 텍스처에 추가할 수 있습니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Dirt
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 흙
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '289'
ht-degree: 1%

---


# 흙

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-dirt-18-n-d.png)

**내부:** 마모 및 완료

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

**Dirt 필터**&#x200B;를 사용하여 재질 위에 Dirt을 추가합니다. **Dirt 필터**&#x200B;은(는) 재질이 오래되고 관심을 받지 않는 것처럼 보이게 하는 데 유용합니다.

![](../../assets/dirt-filter-ceramic-mozaic-tiles-before-tra.png)

위의 깨끗한 타일을 아래의 Dirt 필터에 적용된 것과 비교합니다.

![](../../assets/dirt-filter-ceramic-mozaic-tiles-after-tra.png)

</td>
</tr>
</table>

## 매개변수

<b>기본 매개 변수</b>

* <b>임의화</b>: \
  임의식은 이 필터에서 임의성을 사용하는 다른 매개 변수의 임의값을 결정합니다.

* <b>Dirt 스프레드</b>: 0-1 \
  Dirt으로 덮인 표면적의 범위를 제어합니다

* <b>상위 Dirt 스프레드</b>: 0-1\
  재질의 주름에 초점을 맞추지 않고 Dirt으로 덮인 위쪽 표면을 제어합니다

* <b>Dirt 대비</b>: 0-1 \
  Dirt이 기본 재질과 혼합되는 방식을 제어하기 위해 서로 다른 Dirt 스펙트럼 간의 대비 수준을 조정합니다.

* <b>Dirt 불투명도</b>: 0-1 \
  기본 색상 채널에서 Dirt의 투명도 레벨을 제어합니다. 1은 완전히 불투명합니다.

* <b>Dirt 색상</b>: 0-1 \
  Dirt 색상을 선택합니다.

* <b>Dirt 거칠음</b>: 0-1 \
  재질 표면을 밝고 산란 있게 하는 방법 조정

* <b>Dirt 금속</b>: 0-1 \
  Dirt 표면을 얼마나 반사할지 정의합니다

* <b>Dirt Height</b>: 0-1 \
  Height 맵에 대한 Dirt 영향을 제어합니다

* <b>Dirt 표준 강도</b>: 0-1 \
  Dirt 수준이 표준 맵에 미치는 영향을 제어합니다.

* <b>표면 결함 사용</b>: 전환 \
  서피스 결함 사용을 활성화하거나 비활성화합니다. 활성화되면 추가 컨트롤이 나타납니다.

  <b>표면 결함</b>: 이미지 \
  이미지를 가져와 표면 결함으로 사용하거나, Sampler 에셋 라이브러리에서 기본적으로 제공되는 &quot;Stain&quot; 또는 &quot;Bnw Spots&quot;와 같은 텍스처 생성기를 사용하십시오
