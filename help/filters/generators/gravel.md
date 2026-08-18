---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/gravel.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 자갈 생성기를 사용하여 자갈과 돌 골재 텍스처를 사실적으로 만들 수 있습니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Gravel
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 자갈
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '457'
ht-degree: 0%

---


# 자갈

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-gravel-18-n-d.png)

**내부:** 생성기

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

자갈 필터는 재료 위에 자연스럽게 자갈을 깔아 크레바스를 채웁니다.

이 이미지는 진흙의 크레바스를 자갈로 채우는 데 사용되는 **자갈 필터**&#x200B;를 보여줍니다.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0029-gravel-in.jpg)

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0028-gravel-out.jpg)

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
* **수량**: 0-1\
  재질에 퍼진 자갈의 양을 변경합니다.
* **기본 색상**: 색상 선택\
  자갈 돌의 기본 색상을 선택합니다
* **보조 색상**: 색상 선택\
  자갈 돌의 보조 색상을 선택합니다
* **아래쪽 재질 색상 일치**: 0-1\
  자갈 색상이 밑에 있는 재료의 색상에 영향을 받는 정도를 조정합니다
* **캐비티 마스크 사용**: 토글\
  활성화되면 자갈이 캐비티를 채우고 재료의 높은 부분에 퍼지지 않습니다. 이는 자갈을 더욱 사실적으로 산란시키는 결과를 가져올 수 있다.
* **분산 볼륨 임계값**: 0-50\
  Height 값을 기준으로 분산 볼륨 조정
* **무작위 마스크**: 0-1\
  무작위로 마스킹하도록 자갈 비율을 설정합니다
* **돌 크기**: 1-10\
  돌 크기 제어
* **돌 크기 변형**: 0-1\
  돌 크기의 임의성 제어
* **돌 원형**: 0-1\
  돌을 더 둥글게 또는 더 angular으로 만들기
* **돌 거칠음**: 0-1\
  돌의 거칠기 값 수정
* **돌 Height**: 0-1\
  돌의 Height을 수정합니다. 이것은 돌들이 밑에 있는 물질과 혼합되는 방법에 영향을 준다.
* **석조 고도**: 0-1석재의 기본 고도를 수정합니다. 표고는 돌이 놓여 있는 마루를 설정하며, Height은 돌의 Height을 마루에서 설정합니다.
* **표석 고도 무작위**: 0-1\
  각 돌의 고도에 임의의 값을 추가합니다.
* **표면 Smoothness**: 0-1\
  돌의 윗부분을 부드럽게 만들기
* **사용자 지정 마스크 사용**: 전환\
  사용자 정의 마스크를 사용하여 돌 위치를 페인트할 수 있습니다. 다음 매개 변수는 **사용자 지정 마스크 사용**&#x200B;을 사용하도록 설정한 경우에만 표시됩니다.
  * **마스크 흐림 효과**: 0-1\
    칠한 마스크의 가장자리에 흐림 효과 적용
  * **사용자 지정 마스크**: 이미지/브러시\
    브러시를 클릭하여 돌이 표시될 사용자 정의 마스크를 칠합니다. 사각형을 클릭하여 마스크로 사용할 이미지를 가져옵니다.

**고급 매개 변수**

* **표면 크기(cm)**: 0-1000\
  재질이 나타내는 서피스의 크기를 수정합니다. 표면 크기를 늘린다는 것은 자갈돌의 물리적 크기가 더 크다는 것을 의미하며, 이에 따라 수정될 것이다.
* **Height 깊이** **(cm)**: 0-100\
  재료의 Height 맵으로 표시된 실제 깊이를 수정합니다. Height 깊이가 증가한다는 것은 스톤즈 물리적 크기가 그렇지 않을 때보다 더 크다는 것을 의미하므로, 스톤즈의 정상 강도가 증가된다.
