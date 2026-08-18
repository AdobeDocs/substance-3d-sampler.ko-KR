---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/atlas-creator.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 Atlas Creator 툴을 사용하여 여러 이미지에서 텍스처 아틀라스를 만들어 효율적인 질감 구성을 할 수 있습니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Atlas Creator
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Atlas Creator
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '469'
ht-degree: 0%

---


# Atlas Creator

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-atlasgenerator-18-n-d.png)

**내부:** 도구

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

**Atlas Creator** **filter**&#x200B;를 사용하면 재질과 이미지를 atlas로 변환할 수 있습니다. 그런 다음 **Atlas Scatter** 및 **Atlas Splitter**&#x200B;과 같은 다른 필터를 사용하여 재질 내에서 아틀라스 요소를 사용할 수 있습니다.

아래 이미지는 **Atlas Creator**&#x200B;에서 처리하기 전후의 정글 나뭇잎 지도입니다.

![](../../assets/3d-2d-filters-cropped-0041-atlas-creator-in.jpg)

위의 이미지에서 아틀라스 이미지를 가져와 재질로 변환했지만, 불투명도 맵에서 개별 요소를 고려하지 않으므로 여전히 아틀라스 재질이 아닙니다.

![](../../assets/3d-2d-filters-cropped-0040-atlas-creator-out.jpg)

**Atlas Creator**&#x200B;를 실행하면 불투명도 맵이 생성되고 Atlas 요소 사이의 영역이 기본 색상 채널로 채워집니다.

</td>
</tr>
</table>

매개변수

**기본 매개 변수**

* **작은 모양 제거**: 0-1

  이를 사용하여 아틀라스 내의 최소 오브젝트 크기를 조정합니다. 아티팩트를 제거하는 데 유용합니다.
* **불투명도 - 색차 영향**: 0-2

  색상 값을 기반으로 아틀라스 요소의 가장자리를 미세 조정합니다.
* **불투명도 추가**: 이미지/브러시

  마스크로 사용할 파일을 가져오거나 브러시를 사용하여 **2D 보기**&#x200B;에서 직접 불투명해야 하는 영역을 페인트합니다.

사용 안내서

## 아틀라스 이미지 준비

**Atlas Creator 필터**&#x200B;를 사용하기 전에 Atlas 이미지가 제대로 준비되었는지 확인하는 것이 좋습니다.

**Atlas Creator**&#x200B;는 이미지 색상을 기반으로 작동하며 투명도를 고려하지 않습니다. 즉, 요소 사이의 공간이 일관된 검정 또는 흰색인지 확인하는 것이 아틀라스 이미지를 준비하는 가장 좋은 방법입니다. 그러면 **Atlas 작성자**&#x200B;가 더욱 쉽게 불투명도 마스크를 생성할 수 있습니다.

## 이미지에서 아틀라스 재질 생성

**Atlas Creator**&#x200B;는 Atlas 이미지를 재질 atlas로 변환하도록 설계되었습니다.

1. 소스 이미지를 레이어 스택으로 가져옵니다.
1. 재료 생성 템플릿을 선택하라는 메시지가 표시되면 이미지를 재료로(Image to Material)를 선택합니다. 그렇지 않으면 레이어 스택에 있는 이미지를 사용하여 이미지 위에 **Image to Material(AI 지원) 필터**&#x200B;를 추가합니다.
1. **이미지를 재질로 변환** 필터가 소스 이미지를 재질로 변환할 때까지 기다립니다. 결과가 만족스러울 때까지 매개 변수를 조정합니다.
1. 레이어 스택의 맨 위에 **Atlas Creator 필터**&#x200B;를 추가합니다.
1. 결과가 만족스러울 때까지 **Atlas Creator**&#x200B;의 매개 변수를 조정합니다.

1. 레이어 스택에 이미지를 추가합니다. 재질 제작 템플릿을 선택하라는 메시지가 표시되면 **비트맵으로 사용**&#x200B;을 선택합니다.
1. 이미지 레이어를 선택한 상태에서 **속성 패널**&#x200B;에서 **출력 사용**&#x200B;을 **기본 색상**(으)로 변경합니다.
1. 레이어 스택의 맨 위에 **Atlas 작성자**&#x200B;를 추가합니다.
1. 결과가 만족스러울 때까지 **Atlas Creator**&#x200B;의 매개 변수를 조정합니다. 필터 결과를 더 명확하게 확인하려면 **2D 보기**&#x200B;에서 불투명도 채널을 봅니다.
1. 생성된 채널을 내보내려면 **내보내기 패널**&#x200B;을 사용하십시오.
