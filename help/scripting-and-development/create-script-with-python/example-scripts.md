---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/scripting-and-development/create-a-script-with-python/example-scripts.html"
breadcrumb-title: ''
description: Substance 3D Sampler용 예제 Python 스크립트에 액세스하여 API를 사용하는 방법과 재질 제작 워크플로우를 자동화하는 방법을 알아봅니다.
helpx_creative_field: ""
helpx_description: Sampler > Scripting and Development > Create a Script with Python > Example Scripts
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 예제 스크립트
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '149'
ht-degree: 0%

---


# 예제 스크립트

아래 스크립트를 사용하여 Sampler API의 작동 방식을 이해할 수 있습니다. 워크플로우에 필요한 만큼 언제든지 이 스크립트를 사용하고 추가할 수 있습니다.

## 모두 내보내기

다양한 내보내기 사전 설정으로 재질을 내보냅니다.

### export\_all.py

```
import substance_sampler as ssa 

import os 

import sys 

 

 

## Function to export as SBSAR with default options

def export_as_sbsar(asset_to_export, w_res, h_res, destination_path): 

    asset_to_export.export(w_resolution=w_res, 

                           h_resolution=h_res, 

                           path=destination_path) 

 

 

## Function to export as PNG with Unreal Engine 4 export preset

def export_as_png_with_ue4_preset(asset_to_export, w_res, h_res, destination_path): 

    [ue4_export_preset] = ssa.get_export_presets("Unreal Engine 4") 

    asset_to_export.export(w_resolution=w_res, 

                           h_resolution=h_res, 

                           path=destination_path, 

                           format=ssa.png, 

                           preset=ue4_export_preset) 

 

## Verify if the project is already saved to get its path

if ssa.save_project(): 

    ssa.save_project() 

 

## Get the folder path of the project

    export_path = os.path.dirname(ssa.get_project_path()) 

 

## Get all assets of your project in a list

    all_project_assets = ssa.get_project_assets() 

 

## Go Through the list of all assets

    for asset in all_project_assets: 

## Export each asset with the resolution 2048x2048px next to the project file (.ssa)

        export_as_sbsar(asset, 2048, 2048, export_path) 

 

## Export each asset with the resolution 2048x2048px in a folder "textures" next to the project file (.ssa)

        export_as_png_with_ue4_preset(asset, 2048, 2048, os.path.join(export_path, "textures")) 

else: 

    print("Save first your project", file=sys.stderr) 

 

 
```


## CSV 파일에서 메타데이터 가져오기

이 스크립트는 csv 파일에서 사용자 지정 메타데이터를 가져오고 만듭니다. [material\_physical\_property\_clo.csv](https://helpx.adobe.com/content/dam/help/en/substance-3d/documentation/sadoc/files/234455545/255426646/1/1680276968224/material-physical-property-clo.csv)

### export\_all.py

```
import os 

import csv 

import substance_sampler as ssa 

 

## Set the path where the csv is stored

csv_path = os.path.expanduser('~DocumentsAdobeAdobe Substance 3D Samplermaterial_physical_property_clo.csv') 

print(csv_path) 

 

## Open the CSV file

with open(csv_path, newline='') as csvfile: 

     

## Create a CSV reader object

    reader = csv.DictReader(csvfile) 

     

    current_asset = ssa.get_selected_asset() 

    current_asset.metadata.custom_metadata = {} 

 

## Create an empty dictionnary to store custom metadata

    my_custom_metadata = {} 

## Iterate over each row in the CSV file

    for row in reader: 

        if row['Material'] == current_asset.name: 

            print(current_asset.name) 

 

            for key,value in row.items(): 

## Add a new metadata for each column of the csv file

                my_custom_metadata[key] = value 

                print(key,value) 

            

            current_asset.metadata.custom_metadata = my_custom_metadata   
```


## 모든 색상 매개 변수 표시

이 스크립트는 레이어 스택에 있는 각 레이어의 color 매개 변수를 표시합니다.

### expose\_all\_color\_parameters.py

```
import substance_sampler as ssa 

 

## Get the current asset loaded in the layer stack

my_asset = ssa.get_selected_asset() 

 

## Get all layers of the current asset in the layer stack

my_asset_layers = my_asset.get_layers() 

 

## Go through all layers

for layer in my_asset_layers: 

## Go through all parameters of each layer

    for parameter in layer.parameters: 

## Select color parameters that are visible

        if parameter.widget_type == ssa.color and parameter.visible: 

## Expose the parameter

            parameter.expose(exposed_label=f"{layer.name} - {parameter.label}", exposed_group="") 

 
```


## 레이어 스택 템플릿

이 스크립트는 현재 재질에 정의된 필터 세트를 자동으로 추가합니다.

### layer\_stack\_template.py

```
import substance_sampler as ssa 

 

## Get the current asset loaded in the layer stack

my_current_asset = ssa.get_selected_asset() 

 

## Define my list of filters

[equalizer_filter] = ssa.get_filters("Equalize") 

[tiling_filter] = ssa.get_filters("Tiling") 

[brightness_contrast_filter] = ssa.get_filters("Brightness/Contrast") 

[normal_height_adjustment_filter] = ssa.get_filters("Normal/Height Adjustment") 

[height_to_normal_filter] = ssa.get_filters("Height To Normal") 

 

## Create a list of all filters, starting from bottom to top

layer_stack_template = [equalizer_filter, tiling_filter, brightness_contrast_filter, normal_height_adjustment_filter, 

                        height_to_normal_filter] 

 

## Insert all filters of my template on top of the layer stack

for filter_layer in layer_stack_template: 

## Get the number of layers

    number_of_layers = len(my_current_asset.get_layers()) 

## insert a filter on top of the layer stack (position O is bottom, number of layers is top)

    my_current_asset.insert_filter(filter_layer, number_of_layers) 

    print(f"number of layers: {len(my_current_asset.get_layers())}...")  

 

## Get all layers

my_asset_layers = my_current_asset.get_layers() 

 

## Update two parameters of the Tiling Layer

for layer in my_asset_layers: 

## Filter all layers by the layer name

    if layer.name == "Tiling": 

        print("Layer:", layer.name) 

 

## Check the list of all parameters of the Tiling layer

        for parameter in layer.parameters: 

## Filter the parameters list by the parameter name

            if parameter.label in {"Threshold", "Transform"}: 

                print("Parameter:", parameter.label) 

 

                if parameter.label == "Threshold": 

                    print("Before", parameter.value) 

                    parameter.value = 0.1 

                    print("After:", parameter.value) 

 

                elif parameter.label == "Transform": 

                    print("Before:", parameter.value) 

                    parameter.value = (1.1, 0, 0, 1.1) 

                    print("After:", parameter.value)
```
