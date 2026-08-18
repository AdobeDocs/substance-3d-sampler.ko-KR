---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/height-to-normal.html"
breadcrumb-title: ''
description: Substance 3D Sampler에서 일반 Height 도구를 사용하여 재질 제작 워크플로를 위해 Height 맵을 일반 맵으로 변환할 수 있습니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Height to Normal
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Height을 표준으로
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '312'
ht-degree: 0%

---


# Height을 표준으로

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-heighttonormal-18-n-d.png)

**내부:** 도구

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

Height 채널을 기반으로 일반 채널 데이터를 생성합니다.

아래 이미지에서는 **일반 필터로 Height**&#x200B;를 작동 중입니다.

![](../../assets/h2n-in.jpg)

위의 이미지에는 재질의 정상적인 데이터가 없습니다. Height 맵만 사용할 수 있으며 **2D 보기**&#x200B;에 표시됩니다.

![](../../assets/h2n-out.jpg)

**일반 필터로 Height**&#x200B;을 사용하면 맨 위 이미지에 표시된 Height 맵에서 일반 데이터가 생성됩니다. 생성된 표준 맵 덕분에 두 번째 이미지의 재질에서 빛이 더욱 사실적으로 반사됩니다.

</td>
</tr>
</table>

## 매개변수

**기본 매개 변수**

* **세계 단위 사용**: 전환\
  실제 단위를 사용하여 매개변수를 측정할지 여부를 변경합니다. 그러면 사용 가능한 매개 변수가 수정됩니다.
  * **세계 단위 사용이 활성화된 경우:**
    * **표면 크기(cm)**: 0-500\
      UV 공간의 크기를 세계 단위로 설정
    * **Height 깊이(cm)**: 0-10\
      Height 맵으로 나타내는 거리를 설정합니다. Height 맵이 작은 거리를 나타내는 경우 Height 맵 값의 큰 차이가 일반 각도에 작은 영향을 줄 수 있습니다. Height 맵이 큰 거리를 나타내는 경우, Height 맵 값의 작은 차이가 일반 맵에서 큰 각도를 나타낼 수 있다.
  * **세계 단위 사용이 비활성화된 경우:**
    * **강도**: 0-3\
      법선 각도의 경사를 조정합니다
* **아래쪽 표준 결합**: 0-1\
  기존의 일반 맵을 이 필터의 결과에 추가합니다.

**마스크**

* **사용자 지정 마스크**: 토글\
  사용자 정의 마스크 사용을 활성화하거나 비활성화합니다. 활성화하면 다음 매개변수가 나타납니다.
  * **마스크**: 이미지/브러시\
    마스크로 사용할 이미지를 선택하거나 브러시를 사용하여 2D 보기에서 직접 사용자 정의 마스크를 칠합니다
  * **사용자 지정 마스크 - 흐림 효과**: 0-1\
    마스크에 흐림 효과 적용
  * **사용자 지정 마스크 - 반전**: 전환\
    마스크 반전
