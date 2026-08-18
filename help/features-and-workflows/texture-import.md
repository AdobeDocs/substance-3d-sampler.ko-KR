---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/features-and-workflows/texture-import.html"
breadcrumb-title: ''
description: 텍스처를 Substance 3D Sampler으로 가져와 재질 제작 워크플로우에서 기존 이미지 파일을 사용하는 방법에 대해 알아봅니다.
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > Texture Import
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 텍스처 가져오기
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '273'
ht-degree: 4%

---


# 텍스처 가져오기

![](../assets/Capture-decran-2025-02-19-162128.png.img.png)

**텍스처 가져오기** 템플릿은 여러 이미지를 로드하고 해당 파일 이름에 따라 올바른 출력 채널에 자동으로 연결합니다.

채널 일치는 아래에 설명된 특정 이름 지정 규칙을 기반으로 합니다. 일치하는 내용이 없는 중복 또는 텍스처의 경우 인터페이스에서 이미지가 표시됩니다.

## OpenPBR

Sampler은 다음 OpenPBR 식별자가 있는 파일을 재질의 해당 채널과 일치시킵니다.

>[!NOTE]
>
> Height 채널 식별자는 ASM에 사용되는 식별자와 동일합니다.


| OpenPBR 식별자 | SBSAR 사용 |
| --- | --- |
| base_weight | baseWeight |
| base_color | baseColor |
| base_metalness | 금속/금속 |
| base_diffuse_roughness | baseDiffuseRoughness |
| Specular_weight | specularWeight |
| Specular_색상 | specularColor |
| Specular_거칠음 | 반사거칠음/거칠음 |
| Specular_거칠음_비등방성 | 반사거칠기이방성/이방성 레벨 |
| Specular | 반사 IOR/IOR |
| transmission_weight | transmissionWeight |
| transmission_color | transmissionColor/absorptionColor |
| transmission_깊이 | transmissionDepth/absorptionDistance |
| transmission_산란 | transmissionScatter |
| transmission_산란_비등방성 | transmissionScatterAnisotropy |
| transmission_dispersion_scale | transmissionDispersionScale |
| transmission_dispersion_abbe_number | transmissionDispersionAbbeNumber |
| subsurface_weight | subsurfaceWeight/translucency |
| subsurface_color | subsurfaceColor/scatteringColor |
| subsurface_radius | subsurfaceRadius/scatteringDistance |
| subsurface_radius_scale | subsurfaceRadiusScale/scatteringDistanceScale |
| subsurface_산란_비등방성 | subsurfaceScatterAnisotropy |
| coat_weight | coatWeight/coatOpacity |
| coat_color | coatColor |
| coat_rough | coatRough |
| coat_roughness_비등방성 | coatRoughnessAnisotropy |
| coat_ior | coatIOR |
| 코트 어둡게 하기 | coatDarkening |
| fuzz_weight | fuzzWeight/shenOpacity |
| fuzz_color | fuzzColor/shenColor |
| 퍼지_거칠음 | fuzzRoughness/shenRoughness |
| emission_weight | emissionWeight |
| emission_luminance | emissionLuminance |
| emission_color | emissionColor/emission |
| thin_film_weight | thinFilmWeight |
| thin_film_Thickness | thinFilmThickness |
| thin_film_ior | thinFilmIO |
| 불투명도 | 불투명도 |
| 얇은 벽 | 얇은 벽 |
| 표준 | 표준 |
| 접선 | 접선 |
| coat_normal | coatNormal |
| coat_tangent | coatTangent |

## Adobe Standard Material

다음은 각 채널에 대해 지원되는 파일 이름 지정 규칙 목록입니다.

| **채널** | **Adobe 표준 재질** |
| --- | --- |
| **주변 오클루전** | <ul><li>양쪽융기</li><li>ao</li><li>오클루전</li><li>ambient_오클루전</li></ul> |
| **기본 색상** | <ul><li>기본 색상</li><li>색상</li><li>알베도</li><li>base_color</li><li>베이스</li><li>대열</li><li>색상</li><li>base_color</li><li>기본 색상</li></ul> |
| **확산** | <ul><li>산만해</li><li>diff</li></ul> |
| **발광** | <ul><li>배출</li></ul> |
| **광택** | <ul><li>광택</li><li>광택</li></ul> |
| **Height** | <ul><li>Height</li><li>heightmap</li><li>변위</li><li>디스프</li></ul> |
| **금속** | <ul><li>금속</li><li>mtl</li><li>금속성</li></ul> |
| **표준** | <ul><li>표준</li><li>nrm</li></ul> |
| **불투명도** | <ul><li>불투명도</li><li>alpha</li></ul> |
| **거칠음** | <ul><li>거칠음</li><li>거친</li></ul> |
| **Specular** | <ul><li>Specular</li><li>spec</li></ul> |
| **Specular level** | <ul><li>특별 수준</li><li>Specular_level</li></ul> |

