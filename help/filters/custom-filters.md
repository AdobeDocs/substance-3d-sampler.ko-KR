---
helpx_url: 'https://helpx.adobe.com/substance-3d-sampler/filters/custom-filters.html'
breadcrumb-title: ''
description: Substance 3D Sampler에서 사용자 정의 필터를 사용하여 Substance Designer 필터 및 사용자 정의 효과와 함께 기능을 확장하는 방법을 알아봅니다.
helpx_creative_field: ''
helpx_description: Sampler > Filters > Custom Filters
helpx_experience_level: ''
helpx_learn_topic: ''
helpx_tags: ''
title: 사용자 정의 필터
user-guide-description: ''
user-guide-title: ''
source-git-commit: dc832dc546735437051226f4e1e731b55147b3ea
workflow-type: tm+mt
source-wordcount: '496'
ht-degree: 1%

---


# 사용자 정의 필터

## Substance 지정 필터

레이어 스택 작업의 *가져오기* 단추를 통해 Adobe Substance 3D Designer으로 만든 필터를 가져올 수 있습니다.

### Substance 필터 만들기

필터는 Designer으로 가져온 후 제대로 작동하려면 Sampler에서 특정 방식으로 빌드해야 합니다.

필터의 입력 및 출력 노드에는 식별자 또는 사용이 정의되어 있어야 합니다.

>[!NOTE]
>
> **사용량** 또는 **식별자**(사용량이 우선 순위)을 사용할 수 있습니다.

#### 형식

필터를 Substance 보관 파일(.SBSAR)로 내보내기

>[!NOTE]
>
> Sampler에서 직접 필터를 제어하기 위해 필터 매개 변수를 표시할 수 있습니다. [여기](https://experienceleague.adobe.com/en/docs/substance-3d-designer/using/substance-graphs/manage-parameters/exposing-a-parameter)에서 방법 보기

#### 이미지를 수정할 필터 만들기

![](../assets/image-template.png)

| 이미지 이름 | 사용 |
| --- | --- |
| *Scan1* | **scan1** |
| *스캔2* | **scan2** |
| *...* | **...** |

#### 필터를 생성하여 채널 수정

![](../assets/material-template.png)

| 채널 이름 | 사용 |
| --- | --- |
| *기본 색상* | **기본 색상** |
| *확산* | **확산** |
| *Specular* | **Specular** |
| *Specular level* | **specularlevel** |
| *금속* | **금속** |
| *거칠음* | **거칠음** |
| *광택* | **광택** |
| *표준* | **표준** |
| *Height* | **Height** |
| *주변 오클루전* | **ambientOcclusion** |
| *불투명도* | **불투명도** |

>[!IMPORTANT]
>
> Sampler용 사용자 정의 필터를 만드는 경우 Substance 그래프에 다음 사용자 데이터를 추가해야 합니다.
>
> alchemist::type=filter;

>[!IMPORTANT]
>
> 패키지에서 이미지를 처리할 그래프(scan1에서 scanX로) 하나와 재료를 처리할 그래프(PBR 채널)가 있는 경우, Sampler은 레이어 스택에서 필터가 삽입된 위치에 따라 올바른 그래프를 선택할 수 있습니다.
>
> &quot;이미지&quot; 그래프에 다음 사용자 데이터를 추가합니다.
>
> * 연금술사::type=filter;연금술사::variation::type=multi
>
> &quot;재질&quot; 그래프에 다음 사용자 데이터를 추가합니다.
>
> * 연금술사::type=filter;연금술사::variation::type=material

### 전용 파라미터

특정 매개 변수는 응용 프로그램에서 전역적으로 관리됩니다. 이는 사용자 정의 필터에서 응용 프로그램, 프로젝트 및 레이어 스택의 전역 매개 변수를 사용하는 방법입니다.

#### 표준 포맷

응용 프로그램에 대한 일반 형식을 제어합니다. Sampler에서 DirectX으로 설정

**매개 변수 식별자**: normalformat, normal_format, $normalformat, $normal_format

#### 입력 카운트

이미지를 수정하려는 경우(scan1에서 scanX로) **이미지 수** 매개 변수를 사용하여 레이어 스택의 이미지 수를 사용할 수 있습니다.

* **매개 변수 식별자**: input_count
* **매개 변수 형식**: integer1

#### 재료 입력

Atlas Scatter 또는 스플래터와 같이 레이어 스택에 재질 슬롯을 표시하려면:

* 새 입력 노드 세트 추가(기본 색상, 표준, ... )
* 배경의 모든 입력 노드(레이어 스택의 아래쪽 재질)는 그룹 **재질1**&#x200B;에 있어야 합니다.
* 여러 재질 슬롯을 원하는 경우 맨 위에 추가하려는 첫 번째 재질의 모든 입력 노드는 그룹 **재질2** 등에 있어야 합니다.
* 재료 입력 매개변수를 추가합니다.
  * **매개 변수 식별자**: material_input
  * **매개 변수 형식**: integer1

#### 작업 과정 유형

프로젝트의 작업 과정에 따라 일부 매개 변수를 표시하거나 숨기려는 경우(PBR 금속/거칠기 또는 PBR Specular/광택) [작업 과정 유형] 매개 변수를 사용할 수 있습니다

**매개 변수 식별자**: workflow_type

**매개 변수 형식**: integer1, 드롭다운 목록

옵션:

* 0: PBR 금속/거칠음
* 1: PBR Specular/광택

![](../assets/workflow-type.jpg){width="300px"}
