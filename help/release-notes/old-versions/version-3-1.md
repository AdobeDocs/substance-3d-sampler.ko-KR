---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/old-versions/version-3-1.html"
breadcrumb-title: ''
description: 색상 피커, SVG 지원 및 상호 운용성 개선 사항에 대해 알아보려면 Substance 3D Sampler 버전 3.1의 릴리스 정보를 검토하십시오.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Old Versions > Version 3.1
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 버전 3.1
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '791'
ht-degree: 0%

---


# 버전 3.1

Adobe Substance 3D Sampler 3.1에서는 새로운 색상 피커를 도입하고 SVG 파일을 지원하며 Stager, Photoshop 및 Illustrator과의 상호 운용성을 개선했습니다.

출시일: *2021년 9월 28일*

## 주요 기능

### 색상 피커

이 릴리스에는 스포이드와 색상 견본 지원이 포함된 새 [색상 피커](../../interface/tools-and-widgets/color-picker.md)가 추가되었습니다.

색상을 선택해야 할 때마다 [색상 피커]가 나타납니다. 화면의 어느 곳으로든 이동할 수 있습니다.

![](../../assets/color-picker-raw.png){width="250px"}

### SVG 지원

이제 Sampler에서 SVG 파일을 지원합니다. 에셋, 레이어 스택 또는 레이어의 이미지 입력에 직접 가져올 수 있습니다.

![](../../assets/svg-support.jpg){width="500px"}

### Illustrator에서 편집

새로운 &quot;편집 위치&quot; 기능을 통해 가져온 이미지를 유연하게 업데이트할 수 있습니다. SVG 파일을 조정하려면 Illustrator에서 파일을 직접 편집하면 됩니다. Sampler이 새 SVG으로 시각적 개체를 즉시 업데이트합니다.

### 새 자르기 UX/UI

이제 Sampler에 적절하고 개선된 [자르기] 위젯이 제공되어 자른 영역을 쉽게 정의할 수 있습니다. 정사각형이 아닌 이미지를 정사각형 텍스처로 자를 때도 확장 결과가 나타나지 않습니다.

![](../../assets/crop-9.jpg){width="500px"}

### 표준 포맷

기본 설정을 편집하여 워크플로우에 필요한 [표준 형식](../../interface/preferences/normal-format.md)을 설정합니다. 표준은 환경 설정에서 선택한 형식으로 가져오고 표시하고 내보냅니다.

![](../../assets/7-normal-format-preferences.jpg){width="250px"}

### SBSAR에서 재질 속성 내보내기

셰이더 설정의 모든 재질 매개 변수(표준 비율, Height 비율, Height 수준 등) 을(를) SBSAR 파일로 내보내 Substance 3D Stager에서 읽으면 재질 일치를 확인할 수 있습니다.

![](../../assets/material-consistency-sa-sg.jpg){width="500px"}

## 릴리스 정보

### 3.1.0 Xocoalt

*(2021년 9월 28일 릴리스)*

**추가됨:**

* [색상 피커] 새로운 색상 피커 UI
* [색상 피커] 현재 색상과 이전 색상을 나란히 미리 봅니다
* [색상 피커] 16진수 색상 입력
* [색상 피커] 색상 미리 보기가 있는 새 스포이드
* [색상 피커] 스포이드는 Sampler 외부의 색상을 선택할 수 있습니다
* [색상 피커] RGB 또는 HSV 색상 공간의 색상 조정
* [색상 피커] 색상 견본 저장 및 관리
* [상호 운용성] 이미지 가져오기 레이어 또는 이미지 매개 변수에서 Illustrator의 이미지 편집
* [상호 운용성] 이미지 가져오기 레이어 또는 이미지 매개 변수에서 Photoshop의 이미지 편집
* [Widget] 새 자르기 위젯
* [위젯] 자르기의 유효성을 검사하려면 Enter 키를 누릅니다
* [위젯] 자르기 위젯은 위젯에 맞게 이미지 크기를 읽고 크기 조정 시 비율을 유지합니다
* [UI] 새로운 회색 음영 슬라이더 UI
* [응용 프로그램] 환경 설정에서 일반 형식 선택 추가
* [응용 프로그램] 이미지 가져오기 레이어의 표준 형식은 환경 설정에 지정된 기본 표준 형식을 따릅니다
* [응용 프로그램] 2D 보기에서는 기본 설정에 지정된 표준 형식에 따라 표준이 표시됩니다
* [응용 프로그램] 표준은 환경 설정에 지정된 표준 형식으로 내보내집니다
* [내보내기] SBS 및 SBSAR 파일 내보내기에 일반 형식 매개 변수를 추가합니다.
* [Export] SBS 및 SBSAR 파일 내보내기에 셰이더 설정을 추가합니다
* [내보내기] 내보낸 SBS 그래프의 기본 해상도를 설정합니다.
* [Compound Filters] 7z로 SSA 필터 패키징
* [컴파운드 필터] 컴파운드 필터에 범주 메타데이터 추가
* [컴파운드 필터] 컴파운드 필터에는 축소판이 포함되어 있을 수 있습니다.
* [컴파운드 필터] [내용 가져오기] 대화 상자에 컴파운드 필터 확장명(.ssafilter)을 추가했습니다.
* [컴파운드 필터] 에셋 패널에서 컴파운드 필터(.ssafilter)를 가져옵니다
* [엔진] Substance 엔진을 v8.2.0으로 업데이트

**고정:**

* [응용 프로그램] 연결된 로컬 폴더가 중단될 수 있습니다.
* [Application] 종료 시 충돌 발생
* [Application] Sampler의 두 인스턴스를 실행할 때 충돌이 발생합니다
* [콘텐츠] 자르기 필터에 임의의 시드 조정 있음
* [콘텐츠] 일부 Substance 재질이 업그레이드되지 않는 경우가 있습니다
* [내보내기] 새로 추가된 사용자 정의 사전 설정을 사용하여 내보낼 때 충돌이 발생함
* [내보내기] 내보내기 팝업에서 패키지의 예상 크기가 누락되었습니다.
* [내보내기] SBS 및 SBSAR 파일을 내보낼 때 메모리 누수 수정
* [컴파운드 필터] 컴파운드 필터에는 중복 입력이 있을 수 있습니다
* [컴파운드 필터] 필터에 충족되지 않은 참조가 있는 경우 충돌이 발생합니다
* [컴파운드 필터] 컴파운드 필터를 사용하여 레이어 스택을 재정렬할 때 충돌이 발생합니다
* [복합 필터] 렌더링이 가끔 중단됩니다
* [이미지 가져오기] 이미지를 가져오면 여러 렌더링이 트리거됩니다
* [레이어] 실행 취소/다시 실행 시 충돌 발생
* [레이어] 기본 재질 추가 시 충돌이 발생합니다
* [레이어] 환경 조명으로 잘못된 이미지를 사용할 때 충돌이 발생합니다
* [레이어] 여러 그래프로 필터를 삽입할 때 중복 가져오기 수정
* [레이어] 레이어 순서를 변경해도 작동하지 않음
* [Project] 완료되지 않은 프로젝트 파일을 로드할 때 충돌이 발생합니다
* [Project] 손상된 프로젝트를 열 때 충돌 발생
* [Project] 일부 에셋이 프로젝트에서 사라질 수 있습니다
* [속성] 누락된 필터의 사전 설정 수정
* [UI] 각도 매개 변수를 설정할 수 없습니다.
* [UI] [에셋] 패널에서 메타데이터 표시를 필터링합니다.
* [UI] 범주별로 그룹화하면 필터가 숨겨집니다.
* [UI] 에셋 패널의 스크롤 문제
* [UI] 이제 내보내기 패널에 스크롤바가 있습니다.
* [UI] 이미지 선택기에서 일부 이미지 형식에 대해 축소판이 표시되지 않습니다.

**알려진 문제:**

* [Realtime Engine 2021] 과도한 계산으로 인해 응용 프로그램이 충돌할 수 있음
* [Realtime Engine 2021] AMD CPU와 Nvidia GPU가 모두 설치된 Windows 시스템에서 Realtime Engine 2021이 충돌합니다
* [색상 피커] 다른 해상도의 두 번째 모니터에서 색상을 선택하는 기능이 작동하지 않을 수 있습니다
