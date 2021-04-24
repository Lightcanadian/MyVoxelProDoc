# Voxel Pro Noise

**For all setup displayed here, they were not optimise for actual generation and might give oversize generation. In most case the issue can be fix by adding a "2D Noise SDF" node just before "Set value"**

## 2D Cellular Noise

Setup:

<img src="Images/2021-04-23%2018_48_27-Window.png" alt="Image" width="500"/>

> Not All Picture Has The Same Zoom Factor

| Node setting Dist Func        | Node setting Return type  | Output                                        |
| ----------------------------- | ------------------------- | --------------------------------------------- |
|Eucledean                      |Cell Value                 |<img src="Images/2021-04-23-19_06_13-Window.png" alt="Image" width="200"/>|
|Eucledean                      |Distance                   |<img src="Images/2021-04-23-21_09_51-Window.png" alt="Image" width="200"/>|
|Eucledean                      |Distance 2                 |<img src="Images/2021-04-23-21_10_50-Window.png" alt="Image" width="200"/>|
|Eucledean                      |Distance 2Add              |<img src="Images/2021-04-23-21_11_40-Window.png" alt="Image" width="200"/>|
|Eucledean                      |Distance 2Sub              |<img src="Images/2021-04-23-21_15_05-Window.png" alt="Image" width="200"/>|
|Eucledean                      |Distance 2Mul              |<img src="Images/2021-04-23-21_17_09-Window.png" alt="Image" width="200"/>|
|Eucledean                      |Distance 2Div              |<img src="Images/2021-04-23-21_18_05-Window.png" alt="Image" width="200"/>|
|Manathan                       |Cell Value                 |<img src="Images/2021-04-23-19_09_57-Window.png" alt="Image" width="200"/>|
|Manathan                       |Distance                   |<img src="Images/2021-04-23-21_23_08-Window.png" alt="Image" width="200"/>|
|Manathan                       |Distance 2                 |<img src="Images/2021-04-23-21_24_00-Window.png" alt="Image" width="200"/>|
|Manathan                       |Distance 2Add              |<img src="Images/2021-04-23-21_25_07-Window.png" alt="Image" width="200"/>|
|Manathan                       |Distance 2Sub              |<img src="Images/2021-04-23-21_27_47-Window.png" alt="Image" width="200"/>|
|Manathan                       |Distance 2Mul              |<img src="Images/2021-04-23-21_28_11-Window.png" alt="Image" width="200"/>|
|Manathan                       |Distance 2Div              |<img src="Images/2021-04-23-21_29_06-Window.png" alt="Image" width="200"/>|
|Natural                        |Cell Value                 |<img src="Images/2021-04-23-19_11_08-Window.png" alt="Image" width="200"/>|
|Natural                        |Distance                   |<img src="Images/2021-04-23-21_46_44-Window.png" alt="Image" width="200"/>|
|Natural                        |Distance 2                 |<img src="Images/2021-04-23-21_47_24-Window.png" alt="Image" width="200"/>|
|Natural                        |Distance 2Add              |<img src="Images/2021-04-23-21_48_01-Window.png" alt="Image" width="200"/>|
|Natural                        |Distance 2Sub              |<img src="Images/2021-04-23-21_48_38-Window.png" alt="Image" width="200"/>|
|Natural                        |Distance 2Mul              |<img src="Images/2021-04-23-21_49_29-Window.png" alt="Image" width="200"/>|
|Natural                        |Distance 2Div              |<img src="Images/2021-04-23-21_50_02-Window.png" alt="Image" width="200"/>|

## 2D Crater Noise
Setup:

<img src="Images/2021-04-23-22_18_16-Window.png" alt="Image" width="500"/>

> Not All Picture Has The Same Zoom Factor

| Output                                        |
| --------------------------------------------- |
|<img src="Images/2021-04-23-22_19_10-VoxelPro - Unreal Editor.png" alt="Image" width="200"/>|

## 2D Crater Noise Fractal
Setup:

<img src="Images/2021-04-23-22_22_36-VoxelPro - Unreal Editor.png" alt="Image" width="500"/>

> Not All Picture Has The Same Zoom Factor

| Output                                        |
| --------------------------------------------- |
|<img src="Images/2021-04-23-22_23_26-VoxelPro - Unreal Editor.png" alt="Image" width="200"/>|

## 2D Cubic Noise
Setup:

<img src="Images/2021-04-23-22_26_45-VoxelPro - Unreal Editor.png" alt="Image" width="500"/>

> In the node, there's a setting for Interpolation but it doesn't seem to do anything

> Not All Picture Has The Same Zoom Factor

| Output                                        |
| --------------------------------------------- |
|<img src="Images/2021-04-23-22_27_05-VoxelPro - Unreal Editor.png" width="200"/>|

## 2D Cubic Noise Fractal
Setup:

<img src="Images/2021-04-23-22_30_32-VoxelPro - Unreal Editor.png" alt="Image" width="500"/>

> Not All Picture Has The Same Zoom Factor

|Fractal Type| Output                                        |
| ---------- | --------------------------------------------- |
| FBM        |<img src="Images/2021-04-23-22_31_03-VoxelPro - Unreal Editor.png" alt="Image" width="200"/>|
| Billow     |<img src="Images/2021-04-23-22_33_05-VoxelPro - Unreal Editor.png" alt="Image" width="200"/>|
| Rigid Multi|<img src="Images/2021-04-23-22_34_11-VoxelPro - Unreal Editor.png" alt="Image" width="200"/>|

## 2D Gavoronoi Noise
Setup:

<img src="Images/2021-04-23-22_39_10-VoxelPro - Unreal Editor.png" alt="Image" width="500"/>

> In the node, there's a setting for Interpolation but it doesn't seem to do anything

> Not All Picture Has The Same Zoom Factor

| Output                                        |
| --------------------------------------------- |
|<img src="Images/2021-04-23-22_40_21-VoxelPro - Unreal Editor.png" width="200"/>|

## 2D Gavoronoi Noise Fractal
Setup:

<img src="Images/2021-04-23-22_43_13-VoxelPro - Unreal Editor.png" alt="Image" width="500"/>

> In the node, there's a setting for Interpolation but it doesn't seem to do anything

> Not All Picture Has The Same Zoom Factor

| Output                                        |
| --------------------------------------------- |
|<img src="Images/2021-04-23-22_43_34-VoxelPro - Unreal Editor.png" width="200"/>|

## 2D IQ Noise
Setup:

<img src="Images/2021-04-23-22_59_40-VoxelPro - Unreal Editor.png" alt="Image" width="500"/>

> In the node, there's a setting for Interpolation but it doesn't seem to do anything

> Not All Picture Has The Same Zoom Factor

| Output                                        |
| --------------------------------------------- |
|<img src="Images/2021-04-23-23_00_00-VoxelPro - Unreal Editor.png" width="200"/>|

## 2D Perlin Noise
Setup:

<img src="Images/2021-04-23-23_07_41-VoxelPro - Unreal Editor.png" alt="Image" width="500"/>

> In the node, there's a setting for Interpolation but it has minimal impact on the generation

> Not All Picture Has The Same Zoom Factor

| Output                                        |
| --------------------------------------------- |
|<img src="Images/2021-04-23-23_08_23-VoxelPro - Unreal Editor.png" width="200"/>|

## 2D Perlin Noise Fractal
Setup:

<img src="Images/2021-04-23-23_17_53-VoxelPro - Unreal Editor.png" alt="Image" width="500"/>

> In the node, there's a setting for Interpolation but it has minimal impact on the generation

> Not All Picture Has The Same Zoom Factor

| Output                                        |
| --------------------------------------------- |
|<img src="Images/2021-04-23-23_18_12-VoxelPro - Unreal Editor.png" width="200"/>|

## 2D Simplex Noise
Setup:

<img src="Images/2021-04-23-23_19_58-VoxelPro - Unreal Editor.png" alt="Image" width="500"/>

> In the node, there's a setting for Interpolation but it has minimal impact on the generation

> Not All Picture Has The Same Zoom Factor

| Output                                        |
| --------------------------------------------- |
|<img src="Images/2021-04-23-23_20_46-VoxelPro - Unreal Editor.png" width="200"/>|

## 2D Simplex Noise Fractal
Setup:

<img src="Images/2021-04-23-23_24_45-VoxelPro - Unreal Editor.png" alt="Image" width="500"/>

> In the node, there's a setting for Interpolation but it has minimal impact on the generation

> Not All Picture Has The Same Zoom Factor

| Output                                        |
| --------------------------------------------- |
|<img src="Images/2021-04-23-23_25_23-VoxelPro - Unreal Editor.png" width="200"/>|

## 2D Value Noise
Setup:

<img src="Images/2021-04-23-23_32_26-VoxelPro - Unreal Editor.png" alt="Image" width="500"/>

> In the node, there's a setting for Interpolation but it has minimal impact on the generation

> Not All Picture Has The Same Zoom Factor

| Output                                        |
| --------------------------------------------- |
|<img src="Images/2021-04-23-23_32_45-VoxelPro - Unreal Editor.png" width="200"/>|

## 2D Value Noise Fractal
Setup:

<img src="Images/2021-04-23-23_33_57-VoxelPro - Unreal Editor.png" alt="Image" width="500"/>

> In the node, there's a setting for Interpolation but it has minimal impact on the generation

> Not All Picture Has The Same Zoom Factor

| Output                                        |
| --------------------------------------------- |
|<img src="Images/2021-04-23-23_34_19-VoxelPro - Unreal Editor.png" width="200"/>|