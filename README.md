# AutoBlendLight

下の言語をクリックすると説明を展開できます。  
点击下面的语言即可展开说明。  
Click a language below to expand the documentation.

<details>
<summary><strong>日本語 - クリックして表示</strong></summary>

## 概要

**AutoBlendLight** は、AviUtl2 用の自動背景なじませスクリプトです。  
主に立ち絵や、背景の光に合わせて馴染ませたいオブジェクトを想定しています。

使用者が設定したライティング範囲の中心から、背景の色と明るさをリアルタイムで取得し、ライティングと背景になじませる処理を自動で行います。  
光源の明滅にも連動できます。

## インストール方法

1. 使用する `.anm2` ファイルを次のフォルダへ配置します。フォルダがない場合は作成してください。  
   `ProgramData\aviutl2\Script\AutoBlendLight\`
2. AviUtl2 を再起動します。

### ファイル

- `AutoBlendLight.anm2`：日本語
- `AutoBlendLight_CN.anm2`：中国語
- `AutoBlendLight_EN.anm2`：英語

## 基本操作

### オブジェクト

元のオブジェクトの明るさを調整し、ライティングや背景になじませる処理を加える前の状態を整えます。

### ライティング

設定した範囲の中心から取得した背景色と明るさをもとに、オブジェクトへ光を加えます。  
柔らかいグラデーションと、輪郭をはっきり見せる縁取りの2種類を選べます。  
背景の明るさに連動させることで、点滅するランプなどの光も反映できます。

### ライティング範囲

背景の色と明るさを取得する位置と、ライティングを適用する範囲を指定します。  
中心と範囲はプレビュー上で直接操作できます。

### 背景なじませ

現在の背景をぼかしてオブジェクトへ馴染ませ、立ち絵などが背景から浮いて見えるのを抑えます。

### 固定光源

ライティング範囲をオブジェクトに追従させず、画面上の固定位置に置くための機能です。  
窓、街灯、ランプ、モニターなど、位置が動かない光源を表現するときに使用します。

</details>

<details>
<summary><strong>中文 - 点击查看</strong></summary>

## 概要

**AutoBlendLight** 是用于 AviUtl2 的自动融图脚本，主要面向立绘以及其他需要与背景光照融合的对象。  

脚本会从使用者设定的光照范围中心实时取得背景的颜色和亮度，并自动生成光照与背景融合效果。  
还可以联动光源的闪烁。

## 安装方法

1. 将需要使用的 `.anm2` 文件放入下面的文件夹。如果没有该文件夹，可以自行创建。  
   `ProgramData\aviutl2\Script\AutoBlendLight\`
2. 重启 AviUtl2。

### 文件

- `AutoBlendLight.anm2`：日语
- `AutoBlendLight_CN.anm2`：中文
- `AutoBlendLight_EN.anm2`：英语

## 基本操作

### 对象

调整原对象本身的亮度，为后续的光照与背景融合做好基础调整。

### 光照

根据光照范围中心取得的背景颜色和亮度，为对象自动添加光照。  
可以在柔和的渐变效果与轮廓较明确的描边效果之间切换。  
还可以根据背景亮度实时改变光照强度，从而反映闪烁台灯、屏幕、霓虹灯等光源变化。

### 光照区域

指定从哪里取得背景颜色和亮度，同时决定光照的作用范围。  
中心位置和范围都可以直接在预览画面中操作。

### 背景融合

将当前背景进行模糊后融合到对象中，让立绘或其他对象更自然地融入背景，减少与背景之间的割裂感。

### 固定光源

让光照区域不再跟随对象，而是固定在画面中的某个位置。  
适合窗户、路灯、台灯、显示器等位置固定的光源。

</details>

<details>
<summary><strong>English - Click to view</strong></summary>

## Overview

**AutoBlendLight** is an automatic blending script for AviUtl2, mainly intended for character illustrations and other objects that need to blend with the lighting of the background.

The script samples the background color and brightness in real time from the center of the lighting area set by the user, then automatically generates lighting and background-blending effects.  
It can also react to flickering light sources.

## Installation

1. Place the `.anm2` file you want to use in the folder below. Create the folder if it does not exist.  
   `ProgramData\aviutl2\Script\AutoBlendLight\`
2. Restart AviUtl2.

### Files

- `AutoBlendLight.anm2` — Japanese
- `AutoBlendLight_CN.anm2` — Chinese
- `AutoBlendLight_EN.anm2` — English

## Basic Usage

### Object

Adjusts the brightness of the original object before lighting and background blending are applied.

### Lighting

Uses the background color and brightness sampled from the center of the lighting area to add lighting to the object.  
You can choose between a soft gradient style and a sharper outline style.  
The lighting strength can also react to background brightness, allowing flickering lamps, screens, neon lights, and similar sources to affect the object.

### Lighting Area

Defines where the background color and brightness are sampled and where the lighting is applied.  
The center and area can be adjusted directly in the preview.

### Background Blend

Blurs the current background and blends it into the object so character illustrations and other elements feel more naturally integrated with the background.

### Fixed Light

Keeps the lighting area fixed in screen space instead of following the object.  
This is useful for stationary light sources such as windows, street lamps, desk lamps, and monitors.

</details>
