---
helpx_url: "https://helpx.adobe.com/kr/substance-3d-sampler/filters/generators/surface-relief.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 표면 부조 생성기를 사용하여 재질에 엠보싱 및 부조 표면 패턴을 만듭니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Surface Relief
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 표면 부조
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '309'
ht-degree: 0%

---


# 표면 부조

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-surfacerelief-18-n-d.png)

**내부:** 생성기

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

표면 부조 필터를 사용하여 재질에 노이즈를 추가합니다. 이렇게 하면 큰 모양을 분리하거나 시각적으로 흥미를 더할 수 있습니다.

</td>
</tr>
</table>

## 매개변수

<b>기본 매개 변수</b>

* <b>임의화</b>:\
  이 필터의 다른 모든 임의 매개 변수가 기반으로 하는 임의 초기값입니다.
* <b>강도</b>: 0-1\
  노이즈 진폭 변경
* <b>흐림 강도</b>: 0-1\
  노이즈에 적용된 흐림 효과의 강도입니다
* <b>표면 결함 </b>: 이미지/브러시/텍스처 생성기\
  이미지 또는 [텍스처 생성기]를 사용하여 표면 결함으로 사용합니다.

<b>노이즈 매개 변수</b>

* <b>클램프</b>: 0-1\
  특정 범위로 노이즈 고정
* <b>대비</b>: 0-1\
  노이즈 대비 수정
* <b>반전</b>: 전환\
  노이즈의 Height 맵 반전

<b>변형</b>

* <b>타일링</b>: 1-16\
  <b>기본 매개 변수 > 비율</b>과 달리 <b>타일링</b>에서는 노이즈의 인스턴스 수를 관리합니다.
* <b>거울</b>:\
  한 축 또는 두 축을 기준으로 노이즈 미러링
* <b>오프셋</b>:\
  X 및 Y축의 노이즈 위치 변경
* <b>회전</b>:\
  노이즈를 회전합니다. 회전 각도가 스냅되어 여전히 타일링이 가능한지 확인합니다.

<b>마스크</b>

* <b>사용자 지정 마스크 사용</b>: 전환\
  사용자 정의 마스크 컨트롤을 보려면 활성화합니다.
  * <b>마스크</b>: 이미지/브러시/텍스처 생성기\
    마스크로 사용할 이미지를 가져오거나 브러시를 사용하여 <b>2D 보기</b>에서 직접 페인트합니다.
  * <b>사용자 지정 마스크 - 흐림 효과</b>: 0-1\
    마스크에 흐림 효과 적용
  * <b>사용자 지정 마스크 - 반전</b>: 전환

<b>고급 매개 변수</b>

* <b>Height 강도</b>: 0-1\
  기본 재질 높이 맵과 노이즈 높이 맵의 혼합 제어
* <b>Height - 기준 바꾸기</b>: 전환\
  기본 Height 교체 여부 전환
* <b>표준 강도</b>: 0-1\
  노이즈 표준 지도의 강도 조정
* <b>표준 - 기준 바꾸기</b>: 전환\
  기본 표준 맵을 바꿀지 여부 전환
* <b>표준 -방향</b>:\
  일반 생성에 사용할 축 수정
* <b>표준 - 회전 방향</b>
* <b>주변 오클루전 - 강도</b>
* <b>주변 오클루전 - 반경</b>
