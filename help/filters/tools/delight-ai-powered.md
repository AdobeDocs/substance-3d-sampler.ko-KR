---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/delight-ai-powered.html"
breadcrumb-title: ''
description: Substance 3D Sampler에서 AI 기반 Delight 필터를 사용하여 이미지에서 조명 정보를 제거하고 중립적인 기본 재질을 만들 수 있습니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Delight (AI Powered)
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 딜라이트(AI 기반)
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '393'
ht-degree: 0%

---


# 딜라이트(AI 기반)

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-lightgeneric-18-n-d.png)

**내부:** 도구

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

[딜라이터]를 사용하면 기본 색상 채널에서 조명 정보를 제거할 수 있습니다. 일반적으로 재질은 조명 정보를 포함하지 않아야 하기 때문에 이미지를 재질로 변환할 때 중요합니다. 물질은 빛이 표면에 어떻게 반응해야 하는지 설명하는 정보 집합체이므로, 빛 정보가 없어야 할 채널에 주입되는 빛 정보가 이미 있다면, 표면을 사실적으로 나타내는 물질의 능력을 깨뜨릴 수 있습니다.

***1}Delight(AI 기반) 필터**에서 처리되기 전과 후의 이미지 예. **어두운 영역과 밝은 영역은 제거되었고 기본 색상만 남았습니다.*

![](../../assets/120-0-comparison.png)

아래 이미지는 **Delight(AI 지원) 필터**&#x200B;에서 처리하기 전과 후의 자료를 보여 줍니다.

![](../../assets/3d-2d-filters-cropped-0043-delighter-in.jpg)

상기 이미지에서, 재료는 여전히 기본 색상 채널에 상당한 양의 조명 정보를 포함한다. 기본 색상 채널에는 벽돌 사이의 어두운 그림자가 없어야 합니다.

![](../../assets/3d-2d-filters-cropped-0042-delight-out.jpg)

밝게 하는 패스 이후에 그림자가 제거되어 물리적으로 더 정확한 기본 색상 채널이 만들어졌습니다. 이 예제의 결과는 눈에 띄지 않을 수 있지만 이미지를 즐겁게 하는 것은 이미지를 재료로 변환하는 중요한 단계입니다.

소스 이미지에서 빛은 정적인 광원에서 나오지만, 재질은 어떤 각도에서 나오는 빛도 처리할 수 있어야 합니다. 예를 들어 위쪽에서 아래쪽으로 비치는 빛이 있는 소스 이미지가 흐림 단계를 거치지 않고 재질로 변환되면 빛이 아래쪽에서 위쪽으로 비치는 3D 공간에 표시될 수 있습니다. 단일 광원이 있는 경우 동시에 여러 조명에서 그림자를 드리우는 것처럼 보이기 때문에 재질이 빠르게 제자리를 벗어나 보입니다.

</td>
</tr>
</table>

## 매개변수

즐거움은 매개 변수가 없습니다. 자동으로 작동합니다.

## 사용 안내서

어떻게 사용합니까?

레이어 스택의 맨 위에 **Delighter 필터**&#x200B;를 추가합니다.

### 언제 사용합니까?

**Image to Material(B2M)**&#x200B;을(를) 사용할 때 이미지에서 모든 채널을 추출하고 재질을 타일링 가능하게 만들었으면 Delighter를 사용하여 기본 색상에서 조명 정보를 제거합니다. **Image to Material(AI 기반)**&#x200B;에는 즐거움 패스가 포함되어 있으므로 **Delighter(AI 기반) 필터**&#x200B;를 함께 사용할 필요가 없습니다.
