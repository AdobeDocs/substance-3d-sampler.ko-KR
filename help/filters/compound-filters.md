---
helpx_url: 'https://helpx.adobe.com/substance-3d-sampler/filters/compound-filters.html'
breadcrumb-title: ''
description: Substance 3D Sampler에서 복합 필터를 만들고 사용하여 여러 필터를 재사용 가능한 단일 레이어로 결합하는 방법을 살펴보세요.
helpx_creative_field: ''
helpx_description: Sampler > Filters > Compound Filters
helpx_experience_level: ''
helpx_learn_topic: ''
helpx_tags: ''
title: 컴파운드 필터
user-guide-description: ''
user-guide-title: ''
source-git-commit: dc832dc546735437051226f4e1e731b55147b3ea
workflow-type: tm+mt
source-wordcount: '603'
ht-degree: 0%

---


# 컴파운드 필터

이 기능을 사용하면 인터페이스에서 단일 레이어로 표현되고 여러 필터로 구성된 새 유형의 필터를 만들 수 있습니다.

>[!NOTE]
>
> Substance 3D Sampler 3.1.0 이후 지원

## 설명

복합 필터는 .7zip 압축 폴더인 **.ssafilter** 파일입니다.

* json 포맷을 사용하는 설명 파일: **myfilter\_name.json**
* 다음을 포함하는 **리소스** 폴더:
  * 필터 축소판: icon.png
  * 외부 파일 종속성

### 설명 파일 내용

* 이름: 인터페이스에 표시되는 복합 필터 레이블
* ID: 복합 필터의 고유 식별자입니다
* 범주: 에셋을 범주별로 그룹화할 때 에셋 패널에 사용되는 복합 필터의 범주입니다
* 버전: 복합 필터의 버전을 정의하는 증분 번호입니다.
* 노드: 사용할 노드 목록
* 링크: 다른 노드 간의 연결 목록

### 예

```JSON
{ "SamplerFilter":  
 { 
 "Name": "My filter", 
 "Category": "My filter category", 
 "Id": "my_unique_id", 
 "Version": 2, 
 "Node": [ 
        { 
            "Id": "foo", 
            "InternalFilter": "Foo" 
        }, 
        { 
            "Id": "bar", 
            "File": "bar.sbsar" 
        } 
    ], 
    "Link": [ 
        { 
            "From": { "Node": "FilterInput", "Usage": "baseColor" }, 
            "To": { "Node": "foo", "Usage": "baseColor"} 
        }, 
        { 
            "From": { "Node": "FilterInput", "Usage": "normal" }, 
            "To": { "Node": "foo", "Usage": "normal"} 
        }, 
        { 
            "From": { "Node": "foo", "Usage": "baseColor" }, 
            "To": { "Node": "bar", "Usage": "baseColor"} 
        }, 
        { 
            "From": { "Node": "bar", "Usage": "baseColor" }, 
            "To": { "Node": "FilterOutput", "Usage": "baseColor"} 
        }, 
        { 
            "From": { "Node": "foo", "Usage": "normal" }, 
            "To": { "Node": "FilterOutput", "Usage": "normal"} 
        } 
    ] 
}}
```

## 단계별 제작

1. 새 파일 만들기: **my\_new\_filter.json**
1. 이름, ID, 범주 정의...
1. 필요한 노드 목록 정의
1. 외부 파일이 필요한 경우 **.json** 옆에 **resources** 폴더를 만듭니다.
1. **리소스** 폴더에 파일 추가
1. 노드 사이의 링크 목록 작성
1. JSON이 유효한지 확인합니다(오타 없음, 혼수 없음 또는 대괄호 없음)
1. 축소판을 보려면 **리소스** 폴더에 **icon.png** 이미지를 추가하세요.
1. **.json** 파일과 **resources** 폴더를 선택하고 7zip

## 설명서

### 버전

버전 번호를 사용하면 다른 이터레이션을 추적할 수 있습니다. 이전 버전의 복합 필터로 완료한 레이어 스택을 열면 최신 버전으로 업그레이드하라는 알림이 표시됩니다.

### 노드

노드는 Substance 3D Sampler 내부 필터를 참조할 수 있습니다. 노드 간의 링크와 내부 필터 **InternalFilter**&#x200B;의 레이블을 정의하는 데 사용할 고유 식별자 **Id**&#x200B;을(를) 정의합니다.

```JSON
{ 
  "Id": "step1_identifier", 
  "InternalFilter": "Dirt" 
}
```

노드는 Substance 3D Sampler에 없는 SBSAR 파일을 참조할 수 있습니다. 노드 간의 링크를 정의하는 데 사용할 고유 식별자 **Id**&#x200B;과(와) SBSAR 파일의 파일 이름 **파일**&#x200B;을(를) 정의합니다. SBSAR 파일은 .alchfilter 파일 옆의 **resources** 폴더에 있어야 합니다.

```JSON
{ 
  "Id": "step1_identifier", 
  "File": "foo.sbsar" 
}
```

>[!NOTE]
>
> **filterImg** 및 **filterMat**&#x200B;은(는) 노드 ID로 사용할 수 없습니다.

### 링크

링크는 두 개의 노드가 연결되어 있고 두 개의 요소로 구성되는 방법에 대한 설명입니다.

* From: 노드에서 사용할 사용량
* 받는 사람: 노드의 사용 출력

각 요소에는 3개의 속성이 있습니다.

* 노드: 사용할 노드의 **Id**&#x200B;을(를) 선언합니다.
  * 복합 필터의 입력을 설정합니다. 노드 ID는 **FilterInput**&#x200B;입니다.
  * 복합 레이어의 출력을 설정합니다. 노드 Id는 **FilterOutput**&#x200B;입니다.
* 사용법: 사용할 용도를 선언합니다. 세 가지 옵션이 있습니다.
  * 한 번에 한 번만 사용하고 링크로 링크 선언 (baseColor, normal, Height, ambientOcclusion, roughness, metallic, diffuse, Specular, 광택, specularLevel, opacity, emissive, scan1, ...)
  * [&quot;baseColor&quot;, &quot;normal&quot;] 목록을 지정할 수도 있습니다. **From** 목록의 첫 번째 항목이 **To** 목록의 첫 번째 항목과 일치합니다. 등..
  * **\***을(를) 사용하여 Substance 3D Sampler에서 From 노드와 To 노드의 모든 사용에 대해 동일한 사용을 수행하도록 합니다(동일한 노드 간에 단일 링크 및 목록 링크가 가능한 반면 **\***을(를) 다른 링크와 결합할 수 없음).
* 그룹: 노드의 사용량이 여러 배인 경우 그룹 속성을 사용하여 특정 사용량을 선택할 수 있습니다. 예: 혼합 필터의 경우 맨 아래 재질의 baseColor를 가져오려면 *재질1*&#x200B;을 사용하고 맨 위 재질의 baseColor를 가져오려면 *재질2*&#x200B;을 사용합니다.

```JSON
Link between two nodes  
{ 
  "From": { "Node": "node1","Usage": "baseColor", "Group": ""}, 
  "To": { "Node": "node2", "Usage": "baseColor"} 
} 
 
Link between outputs of layers below of the compound filter and the compound filter: 
{ 
  "From": { "Node": "FilterInput", "Usage": "*" }, 
  "To": { "Node": "node1", "Usage": "*"} 
} 

Link to declare outputs of the compound filter: 
{ 
  "From": { "Node": "node1", "Usage": "*" }, 
  "To": { "Node": "FilterOutput", "Usage": "*"} 
}
```
