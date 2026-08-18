---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/adjustments/equalize.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 균일화 필터를 사용하여 명도 값을 다시 분포하고 이미지 대비를 자동으로 향상합니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Equalize
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 균일화
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '417'
ht-degree: 0%

---


# 균일화

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-equalize-18-n-d.png)

**인:** 조정

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

균일화 필터는 거리 범위를 기준으로 로컬 대비를 조정합니다. [균일화] 필터의 목표는 각 채널에서 큰 차이를 줄이는 것입니다. 따라서 일반적으로 B2M(Image to Material) 워크플로우의 일부로 유용합니다. Image to Material(AI 지원) 필터에는 결과를 개선하기 위한 필터 내의 균일화 패스가 포함됩니다.

아래 이미지는 **균일화 필터**&#x200B;를 작동 상태로 보여줍니다.

![](../../assets/3d-2d-filters-cropped-0033-equalizer-in.jpg)

**균일화 필터**&#x200B;가 추가되기 전에 이 재질의 Height 맵과 기본 색상에 상당한 변형이 있습니다.

![](../../assets/3d-2d-filters-cropped-0032-equalizer-out.jpg)

**균일화 필터**&#x200B;가 추가된 후 Height 맵과 기본 색상 채널 모두 세부 사항의 손실 없이 더 균일해집니다.

</td>
</tr>
</table>

## 필터 균일화 튜토리얼

## 매개변수

<b>기본 매개 변수</b>

* <b>입력 바둑판식</b>: 전환\
  이 옵션을 활성화하면 재질이 반복적으로 바둑판식으로 표시된 것처럼 취급되므로 변경 시 테두리 근처에서 변경하면 반대쪽 테두리의 색상 값에 영향을 받습니다.
* <b>반경</b>: 0-1\
  [균일화] 효과를 더 넓은 영역으로 확산합니다.
* <b>색상 혼합</b>: 0-1\
  주변 영역으로 들어오는 색상을 제어합니다.
* <b>로컬 세부 정보</b>: 0-1\
  [균일화] 필터에서 로컬 세부 묘사를 유지하는 방식을 조정합니다.

<b>*채널*</b>

각 채널의 컨트롤은 같은 방식으로 작동합니다.

* <b>공통 매개 변수 재정의</b>: 토글\
  이 채널에 대한 균일화 효과를 사용자 정의하려면 이 옵션을 활성화합니다. 활성화되면 추가 컨트롤이 표시됩니다.
  * <b>입력 바둑판식</b>: 전환\
    이 옵션을 활성화하면 재질이 반복적으로 바둑판식으로 표시된 것처럼 취급되므로 변경 시 테두리 근처에서 변경하면 반대쪽 테두리의 색상 값에 영향을 받습니다.
  * <b>반경</b>: 0-1\
    [균일화] 효과를 더 넓은 영역으로 분산합니다.
  * <b>로컬 차이점 유지</b>: 전환\
    세부 사항을 유지하기 위해 균일화 효과가 더 높은 해상도에서 작동하도록 활성화
* <b>대상 모드</b>:\
  [균일화] 효과를 맞추는 방법을 선택합니다. 기본적으로 [균일화]는 색상을 채널의 평균 색상 방향으로 이동시키려고 시도합니다. 매개 변수를 사용하여 대신 선택한 색상이나 값에 치우치게 합니다. 매개 변수를 선택하면 추가 컨트롤이 표시됩니다.
  * <b>대상</b>: 색상 선택\
    균일화 알고리즘의 대상으로 사용할 색상이나 값을 선택합니다.
* <b>사용자 지정 색상 변형</b>: HSL 슬라이더\
  지정된 채널에 대해 균일화 알고리즘을 실행한 후 결과의 색조, 크로마(채도), 밝기(광도)를 조정합니다.

<b>마스크</b>

* <b>사용자 지정 마스크</b>: 토글\
  이 필터에 대한 사용자 지정 마스크 사용 활성화 또는 비활성화
* <b>사용자 지정 마스크</b>: 이미지/브러시\
  마스크로 사용할 이미지를 선택하거나 브러시를 사용하여 2D 보기에서 직접 사용자 정의 마스크를 칠합니다
* <b>사용자 지정 마스크 반전</b>: 전환
