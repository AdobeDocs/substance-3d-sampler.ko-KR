---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/interface/panels/channel-settings-panel.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 채널 설정 패널을 사용하여 재질 채널을 관리하고 채널 가시성을 제어하는 방법을 알아봅니다.
helpx_creative_field: ""
helpx_description: Sampler > Interface > Panels > Channel Settings panel
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 채널 설정 패널
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '483'
ht-degree: 1%

---


# 채널 설정 패널

<table>
<tr style="border: 0;">
<td style="border: 0; width: 30%" valign="top">


**채널 설정** 패널은 현재 재질에 대해 계산된 채널 목록을 제어합니다. 재질 모델 가시성을 관리하거나, 재질에 채널을 추가 또는 제거하거나, 사용 중인 채널을 변경할 수 있습니다.

</td>
<td style="border: 0;" valign="top">

![채널 설정 패널](../../assets/6.0_ChannelSettingsPanel.png)

</td>
</tr>
</table>

## 재질 모델

이 드롭다운을 사용하여 재질을 렌더링하는 데 사용되는 셰이더 프레임워크를 선택합니다. **재질 모델 설정 패널**&#x200B;의 옵션이 선택한 채널을 기준으로 변경됩니다.

재질 모델을 변경하면 새 모델에 대해 레이어 스택을 다시 계산해야 하며 다른 채널을 사용할 수 있게 됩니다. Sampler은 변환에서 데이터 손실을 최소화하려고 하지만 이러한 변경으로 인해 새 재질 모델과 모양에 미세한 차이가 발생할 수 있습니다.

>[!NOTE]
>
> Adobe ASM(Standard Material)에서 OpenPBR으로 변경할 수 있지만 현재 OpenPBR에서 ASM으로 변경할 수는 없습니다.


## 재질 채널

<table>
<tr style="border: 0;">
<td style="border: 0; width: 30%" valign="top">


이 섹션에는 워크플로우를 기반으로 기본적으로 계산되는 채널 목록이 표시됩니다.

**목록 편집 단추**&#x200B;를 사용하여 **채널 선택**&#x200B;을 열고 재질에 대해 계산되는 채널을 변경할 수 있습니다.

</td>
<td style="border: 0;" valign="top">

![재질 채널 섹션이 강조 표시된 채널 설정 패널](../../assets/6.0_ChannelSettingsPanel_MaterialChannels.png){width="200px"}

</td>
</tr>
</table>

>[!NOTE]
>
> 예를 들어, [Substance Source]의 일부 재질이 불투명도 또는 주변 오클루전 채널을 출력하지 않습니다. 불투명도 채널이 &quot;계산됨&quot;으로 표시되어도 Substance 파일에서 출력되지 않으면 Sampler에서 생성되지 않습니다.

### 채널 선택

채널 선택 창에서 재질에 채널을 추가하거나 제거할 수 있습니다.

![Adobe Standard Material이 재질 모델으로 선택된 채널 선택 창의 스크린샷.](../../assets/6.0_ChannelSelectionWindow.png)

자료에 채널을 추가하려면 사용 가능한 채널을 선택하고 **> 단추**를 사용하세요.
재질에 있는 채널을 제거하려면 **선택한 채널 목록**&#x200B;에서 채널을 선택하고 **&lt; 단추**를 사용하세요.
**≫ 단추**&#x200B;를 사용하여 자료에 사용 가능한 모든 채널을 추가하거나 **≪ 단추**&#x200B;를 사용하여 자료에서 모든 채널을 제거할 수 있습니다.

또한 사전 설정을 사용하여 재질의 채널 목록을 빠르게 선택할 수 있습니다. 기본적으로 Sampler에는 다양한 사전 설정이 포함되어 있지만 직접 만들 수도 있습니다.

1. 재질에 원하는 채널을 추가합니다.
1. **사전 설정으로 저장 단추**&#x200B;를 사용하세요.
1. 사전 설정의 이름을 지정합니다.

>[!NOTE]
>
>사전 설정을 저장하면 사전 설정이 재질에 적용되지 않습니다.

## 사용자 정의 채널

선택한 작업 과정에 기본적으로 포함되지 않는 추가 채널을 토글합니다.

<table>
<tr style="border: 0;">
<td style="border: 0; width: 30%" valign="top">

각 사용자 정의 채널에는 컨트롤을 제어하는 데 사용할 수 있는 두 가지 옵션이 있습니다.

1. [가시성] 토글을 사용하여 2D 보기에서 채널을 표시하거나 숨길 수 있습니다.
2. **자동 단추**&#x200B;를 사용하여 채널이 자동으로 계산되는지 여부를 전환할 수 있습니다.
   * 이 옵션을 켜면 스택에서 채널 위의 레이어가 채널을 요청하면 채널이 계산됩니다.
   * 꺼져 있으면 채널이 항상 계산됩니다.

</td>
<td style="border: 0;" valign="top">

![사용자 지정 채널 섹션이 강조 표시된 채널 설정 패널](../../assets/6.0_ChannelSettingsPanel_CustomChannels.png){width="200px"}


</td>
</tr>
</table>



