---
helpx_url: "https://helpx.adobe.com/kr/substance-3d-sampler/release-notes/old-versions/version-0-7-0.html"
breadcrumb-title: ''
description: 업데이트, 개선 및 버그 수정에 대해 알아보려면 Substance 3D Sampler 버전 0.7.0의 릴리스 정보를 검토하십시오.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Old Versions > Version 0.7.0
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 버전 0.7.0
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '357'
ht-degree: 0%

---


# 버전 0.7.0

출시일: **2019/06/13**

추가됨:

* [필터] 스페이스바를 눌러 필터에 빠르게 액세스할 수 있습니다.
* [필터] 필터를 관리하고 찾아보고 가져올 수 있는 새로운 전용 패널
* [메타데이터] 메타데이터를 보려면 재질을 마우스 오른쪽 버튼으로 클릭합니다.
* [메타데이터] 재질을 마우스 오른쪽 버튼으로 클릭하여 디스크에서 해당 위치를 확인합니다.
* [슬라이더] Ctrl 키를 눌러 슬라이더를 움직일 때 슬라이더에 애니메이션 적용
* [슬라이더] P를 눌러 슬라이더 애니메이션을 중지하고 다시 시작합니다.
* [내보내기] SBSAR 내보내기는 Substance Source 지침을 따릅니다
* [라이선스] 환경 변수를 사용하여 Substance Alchemist 활성화
* [UX] 파일 대화 상자가 마지막으로 선택한 파일 경로를 기억합니다.
* [UX] 폴더 대화 상자가 마지막으로 선택한 폴더 경로를 기억합니다.
* [UI] 리소스 패널 UI 업데이트
* [UI] 검색 막대 UI 업데이트
* [UI] 새 재질 만들기 아이콘이 업데이트됨
* [도움말] URL이 [substance3d.com](http://substance3d.com) 도메인으로 업데이트되었습니다.
* [메쉬] 이제 천 메쉬를 사용할 수 있습니다.
* [내용] 새로운 부식 필터
* [내용] 새로운 Oxydation 필터
* [콘텐츠] 새로운 이끼 필터
* [콘텐츠] 새 Dust 필터
* [콘텐츠] 새로운 벽돌 패턴 필터
* [콘텐츠] 새로운 돌담 패턴 필터
* [콘텐츠] 새로운 나무 마무리 필터
* [콘텐츠] 새로운 메탈 마무리 필터
* [콘텐츠] 새 Snow 필터
* [콘텐츠] 새로운 임의화 필터
* [콘텐츠] 이제 기본 재질 필터에서 바로 텍스처를 가져올 수 있습니다

수정:

* 레이어 스택을 저장할 때 충돌 해결
* 환경 회전 슬라이더에서 1보다 큰 값을 추가할 수 있습니다.
* 블렌드 레이어가 블렌드 레이어에서 재질 레이어로 앞뒤로 변환되면 블렌드 매개 변수를 잃지 마십시오
* 동일한 레이어 스택의 변형을 여러 번 생성할 때 중복 수정
* 재질을 다시 열 때 Alchemist은 슬라이더의 수정된 범위(최소 및 최대)를 기억합니다

알려진 문제:

* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* Delighter 단계의 빠른 가시성 전환은 권장하지 않습니다
* 사용자 정의 환경 가져오기가 검은색으로 바뀔 수 있음
* 이미지 가져오기 레이어의 [속성] 패널에 TIF 이미지가 표시되지 않습니다
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다
* Height에 표준 필터가 MacOS에서 충돌할 수 있음
