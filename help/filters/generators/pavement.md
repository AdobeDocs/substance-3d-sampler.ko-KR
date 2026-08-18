---
helpx_url: "https://helpx.adobe.com/kr/substance-3d-sampler/filters/generators/pavement.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 Painter 생성기를 사용하여 실제 포장 및 재료 노면 텍스처를 생성합니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Pavement
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 인도
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '384'
ht-degree: 1%

---


# 인도

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-pavement-18-n-d.png)

**내부:** 생성기

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

재료를 포장 패턴으로 변환합니다. 포장 필터는 패턴 스타일을 빠르고 쉽게 변경할 수 있는 여러 가지 옵션을 포함합니다.

***포장 필터**&#x200B;의 예*

</td>
</tr>
</table>

## 매개변수

**기본 매개 변수**

* **임의화**:\
  임의식은 이 필터에서 임의성을 사용하는 다른 매개 변수의 임의값을 결정합니다.
* **기본 재질 크기**: 0-1\
  각 벽돌에 사용되는 재질의 비율을 제어합니다
* **벽돌 간격**: 0-1\
  벽돌 사이의 간격 수정
* **모퉁이 원형률**: 0-1\
  벽돌의 모서리를 더 둥글게 만들거나 덜 둥글게 만듭니다.
* **가장자리 원형률**: 0-1\
  벽돌의 가장자리를 매끄럽게 하여 더 마모된 것처럼 보이게 합니다
* **기울기 강도**: 0-1\
  각 벽돌에 적용된 무작위 기울기의 강도 변경
* **임의 상승 강도**: 0-1\
  서로 관련된 벽돌의 Height 변형을 수정합니다.

**패턴**

각 패턴에는 **패턴 유형**&#x200B;에서 패턴을 선택할 때 나타나는 다른 매개 변수 집합이 있습니다. 매개 변수를 실험하여 효과를 확인합니다.

* **패턴 형식**:\
  패턴을 선택하여 벽돌을 배치합니다.

**조인트**

* **공동** **Height**: 0-1\
  벽돌 사이의 재질 Height 수정
* **조인트 너비**: 0-1\
  벽돌 사이의 재질이 벽돌의 가장자리와 겹치는 정도를 조정합니다
* **조인트 너비 변형**: 0-1\
  **조인트 폭**&#x200B;의 임의성 조정
* **조인트 광도**: 0-1\
  벽돌 사이의 재질 모양을 수정합니다. 이 옵션은 마스크 용도로 유용할 수 있습니다.

**고급 매개 변수**

* **표면 강도**: 0-1\
  균열 또는 흠집과 같은 서피스 변형에 대한 수직 강도를 제어합니다.
* **표면 크기(cm)**: 0-1000\
  재질이 나타내는 물리적 크기 조정
* **표면 Height 배율(cm)**: 0-1000\
  Height 맵으로 표시된 물리적 공간 변경
* **표면 Smoothness**: 0-1\
  서피스의 변형 정도와 세부 사항 제어
* **표면 노출**: 0-1\
  Height과 표준을 임의로 수정하여 표면에 손상이나 변형을 추가합니다
* **표면 노출 마스크 임계값**: 0-1\
  **표면 노출**&#x200B;을 제어하는 데 사용되는 마스크의 임계값 수정
* **Scalemap 사용**: 전환\
  비율 맵을 사용하여 위치에 따라 벽돌의 크기를 조정합니다
* **Scalemap 강도**: 0-1\
  스케일 맵이 벽돌 크기에 미치는 영향을 조정합니다.
