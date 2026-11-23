<p align="right"><a href="README.md">English</a> · <a href="README.ja.md">日本語</a> · <b>中文</b></p>

<p align="center"><img src="icon.jpg" width="180"></p>

<h1 align="center">Yuri Face Tracking</h1>

<p align="center">mFT v2.0.0-native for <b>悠莉 - Yuri - by VISIONTOKYO</b></p>

<p align="center"><a href="https://mustarlabs.booth.pm/items/8926576">mFT on BOOTH</a> · <a href="https://visiontokyo.booth.pm/items/8670449">【オリジナル3Dモデル】悠莉-Yuri-</a> · <a href="https://youtu.be/OH4fnlD3O7s">Demo video</a></p>

<p align="center"><b>Thanks to VISIONTOKYO for the green light to make face tracking for Yuri.</b></p>
<p align="center">制作を快諾してくださった VISIONTOKYO さまに感謝します。</p>

## Expressions

FT shapes, each looping 0 → 1 → 0. Left and right are as you look at the avatar (its own left shows on your right).  
FT シェイプ (0 → 1 → 0)。左右は見ている人から見た向き。

<table>
<tr><td align="center"><img src="expressions/EyeClosedRight.webp" width="200"><br><sub>EyeClosed (left)</sub></td><td align="center"><img src="expressions/EyeWideRight.webp" width="200"><br><sub>EyeWide (left)</sub></td><td align="center"><img src="expressions/EyeSquintRight.webp" width="200"><br><sub>EyeSquint (left)</sub></td><td align="center"><img src="expressions/Brows_Up.webp" width="200"><br><sub>BrowInnerUp · BrowOuterUp (left, right)</sub></td></tr>
<tr><td align="center"><img src="expressions/Brows_DownPinch.webp" width="200"><br><sub>BrowDown · BrowPinch (left, right)</sub></td><td align="center"><img src="expressions/CheekPuffRight.webp" width="200"><br><sub>CheekPuff (left)</sub></td><td align="center"><img src="expressions/JawOpen.webp" width="200"><br><sub>JawOpen</sub></td><td align="center"><img src="expressions/JawForward.webp" width="200"><br><sub>JawForward (3/4)</sub></td></tr>
<tr><td align="center"><img src="expressions/MouthSmile.webp" width="200"><br><sub>MouthSmile</sub></td><td align="center"><img src="expressions/MouthFrown.webp" width="200"><br><sub>MouthFrown</sub></td><td align="center"><img src="expressions/MouthUpperUpLowerDown.webp" width="200"><br><sub>MouthUpperUp + MouthLowerDown</sub></td><td align="center"><img src="expressions/MouthLeft.webp" width="200"><br><sub>Mouth (right)</sub></td></tr>
<tr><td align="center"><img src="expressions/LipPucker.webp" width="200"><br><sub>LipPucker</sub></td><td align="center"><img src="expressions/LipFunnel.webp" width="200"><br><sub>LipFunnel</sub></td><td align="center"><img src="expressions/TongueOut.webp" width="200"><br><sub>TongueOut</sub></td><td align="center"><img src="expressions/TongueRadial.webp" width="200"><br><sub>Tongue, all directions</sub></td></tr>
</table>

### All shapes / 全シェイプ

![all shapes](expressions/_all_shapes.webp)

<details><summary>Eyes (6)</summary>

<table>
<tr><td align="center"><img src="expressions/EyeClosedRight.webp" width="200" loading="lazy"><br><sub>EyeClosed (left)</sub></td><td align="center"><img src="expressions/EyeClosedLeft.webp" width="200" loading="lazy"><br><sub>EyeClosed (right)</sub></td><td align="center"><img src="expressions/EyeWideRight.webp" width="200" loading="lazy"><br><sub>EyeWide (left)</sub></td><td align="center"><img src="expressions/EyeWideLeft.webp" width="200" loading="lazy"><br><sub>EyeWide (right)</sub></td></tr>
<tr><td align="center"><img src="expressions/EyeSquintRight.webp" width="200" loading="lazy"><br><sub>EyeSquint (left)</sub></td><td align="center"><img src="expressions/EyeSquintLeft.webp" width="200" loading="lazy"><br><sub>EyeSquint (right)</sub></td></tr>
</table>

</details>

<details><summary>Brows (2)</summary>

<table>
<tr><td align="center"><img src="expressions/Brows_Up.webp" width="200" loading="lazy"><br><sub>BrowInnerUp · BrowOuterUp (left, right)</sub></td><td align="center"><img src="expressions/Brows_DownPinch.webp" width="200" loading="lazy"><br><sub>BrowDown · BrowPinch (left, right)</sub></td></tr>
</table>

</details>

<details><summary>Cheeks and nose (8)</summary>

<table>
<tr><td align="center"><img src="expressions/CheekPuffRight.webp" width="200" loading="lazy"><br><sub>CheekPuff (left)</sub></td><td align="center"><img src="expressions/CheekPuffLeft.webp" width="200" loading="lazy"><br><sub>CheekPuff (right)</sub></td><td align="center"><img src="expressions/CheekSuckRight.webp" width="200" loading="lazy"><br><sub>CheekSuck (left)</sub></td><td align="center"><img src="expressions/CheekSuckLeft.webp" width="200" loading="lazy"><br><sub>CheekSuck (right)</sub></td></tr>
<tr><td align="center"><img src="expressions/CheekSquintRight.webp" width="200" loading="lazy"><br><sub>CheekSquint (left)</sub></td><td align="center"><img src="expressions/CheekSquintLeft.webp" width="200" loading="lazy"><br><sub>CheekSquint (right)</sub></td><td align="center"><img src="expressions/NoseSneerRight.webp" width="200" loading="lazy"><br><sub>NoseSneer (left)</sub></td><td align="center"><img src="expressions/NoseSneerLeft.webp" width="200" loading="lazy"><br><sub>NoseSneer (right)</sub></td></tr>
</table>

</details>

<details><summary>Jaw (5)</summary>

<table>
<tr><td align="center"><img src="expressions/JawOpen.webp" width="200" loading="lazy"><br><sub>JawOpen</sub></td><td align="center"><img src="expressions/JawRight.webp" width="200" loading="lazy"><br><sub>Jaw (left)</sub></td><td align="center"><img src="expressions/JawLeft.webp" width="200" loading="lazy"><br><sub>Jaw (right)</sub></td><td align="center"><img src="expressions/JawForward.webp" width="200" loading="lazy"><br><sub>JawForward (3/4)</sub></td></tr>
<tr><td align="center"><img src="expressions/JawBackward.webp" width="200" loading="lazy"><br><sub>JawBackward (3/4)</sub></td></tr>
</table>

</details>

<details><summary>Mouth (17)</summary>

<table>
<tr><td align="center"><img src="expressions/MouthSmile.webp" width="200" loading="lazy"><br><sub>MouthSmile</sub></td><td align="center"><img src="expressions/MouthSmile_LR.webp" width="400" loading="lazy"><br><sub>MouthSmile (left, right)</sub></td><td align="center"><img src="expressions/MouthFrown.webp" width="200" loading="lazy"><br><sub>MouthFrown</sub></td><td align="center"><img src="expressions/MouthFrown_LR.webp" width="200" loading="lazy"><br><sub>MouthFrown (left, right)</sub></td></tr>
<tr><td align="center"><img src="expressions/MouthUpperUpLowerDown.webp" width="200" loading="lazy"><br><sub>MouthUpperUp + MouthLowerDown</sub></td><td align="center"><img src="expressions/MouthStretchRight.webp" width="200" loading="lazy"><br><sub>MouthStretch (left)</sub></td><td align="center"><img src="expressions/MouthStretchLeft.webp" width="200" loading="lazy"><br><sub>MouthStretch (right)</sub></td><td align="center"><img src="expressions/MouthPressRight.webp" width="200" loading="lazy"><br><sub>MouthPress (left)</sub></td></tr>
<tr><td align="center"><img src="expressions/MouthPressLeft.webp" width="200" loading="lazy"><br><sub>MouthPress (right)</sub></td><td align="center"><img src="expressions/MouthDimpleRight.webp" width="200" loading="lazy"><br><sub>MouthDimple (left)</sub></td><td align="center"><img src="expressions/MouthDimpleLeft.webp" width="200" loading="lazy"><br><sub>MouthDimple (right)</sub></td><td align="center"><img src="expressions/MouthTightenerRight.webp" width="200" loading="lazy"><br><sub>MouthTightener (left)</sub></td></tr>
<tr><td align="center"><img src="expressions/MouthTightenerLeft.webp" width="200" loading="lazy"><br><sub>MouthTightener (right)</sub></td><td align="center"><img src="expressions/MouthRaiserUpper.webp" width="200" loading="lazy"><br><sub>MouthRaiserUpper</sub></td><td align="center"><img src="expressions/MouthRaiserLower.webp" width="200" loading="lazy"><br><sub>MouthRaiserLower</sub></td><td align="center"><img src="expressions/MouthRight.webp" width="200" loading="lazy"><br><sub>Mouth (left)</sub></td></tr>
<tr><td align="center"><img src="expressions/MouthLeft.webp" width="200" loading="lazy"><br><sub>Mouth (right)</sub></td></tr>
</table>

</details>

<details><summary>Lips (4)</summary>

<table>
<tr><td align="center"><img src="expressions/LipFunnel.webp" width="200" loading="lazy"><br><sub>LipFunnel</sub></td><td align="center"><img src="expressions/LipPucker.webp" width="200" loading="lazy"><br><sub>LipPucker</sub></td><td align="center"><img src="expressions/LipSuckUpper.webp" width="200" loading="lazy"><br><sub>LipSuckUpper</sub></td><td align="center"><img src="expressions/LipSuckLower.webp" width="200" loading="lazy"><br><sub>LipSuckLower</sub></td></tr>
</table>

</details>

<details><summary>Tongue (11)</summary>

<table>
<tr><td align="center"><img src="expressions/TongueOut.webp" width="200" loading="lazy"><br><sub>TongueOut</sub></td><td align="center"><img src="expressions/TongueRadial.webp" width="200" loading="lazy"><br><sub>Tongue, all directions</sub></td><td align="center"><img src="expressions/TongueUp.webp" width="200" loading="lazy"><br><sub>TongueUp</sub></td><td align="center"><img src="expressions/TongueDown.webp" width="200" loading="lazy"><br><sub>TongueDown</sub></td></tr>
<tr><td align="center"><img src="expressions/TongueRight.webp" width="200" loading="lazy"><br><sub>Tongue (left)</sub></td><td align="center"><img src="expressions/TongueLeft.webp" width="200" loading="lazy"><br><sub>Tongue (right)</sub></td><td align="center"><img src="expressions/TongueRoll.webp" width="200" loading="lazy"><br><sub>TongueRoll</sub></td><td align="center"><img src="expressions/TongueUpRightMorph.webp" width="200" loading="lazy"><br><sub>TongueUp (left)</sub></td></tr>
<tr><td align="center"><img src="expressions/TongueUpLeftMorph.webp" width="200" loading="lazy"><br><sub>TongueUp (right)</sub></td><td align="center"><img src="expressions/TongueDownRightMorph.webp" width="200" loading="lazy"><br><sub>TongueDown (left)</sub></td><td align="center"><img src="expressions/TongueDownLeftMorph.webp" width="200" loading="lazy"><br><sub>TongueDown (right)</sub></td></tr>
</table>

</details>


## 中文

### 简介

- Yuri 的嘴、眼、舌、脸颊和眉毛随你的脸而动。为他的脸雕刻了 63 个形态键，另有 12 个由他自己的形态键组合而成。
- Cold、Warm、Kisekae、Makeup 四个版本都能用。
- 一键安装。绝不改动你的原始文件。
- 不包含 Yuri 本体和面捕设备。

mFT 使用我从零编写的模板，是给想要更丰富工具和更强表现力的人的选择。

### 数字及其含义

| 数字 | 含义 |
|---|---|
| 自己 +0.33 ms，他人 +0.30 ms (原生) | 每帧增加的开销。2026-11-20 在干净的场景中测得，请视为上限。经典版 (2026-10-03 测得)：Full 自己 +0.61 ms / 他人 +0.80 ms，Light +0.49 ms / +0.59 ms。 |
| 32 / 256 (原生)、170 / 256 (经典 Full)、145 / 256 (经典 Light) | 同步参数。原生分开计算：他自身 6 + FT 26 (Full) 或 7 (Light)。面部本身 0 bit。Kisekae 经典版：165 / 140。表情每个 1 bit。 |
| 94 个形态键 + 他的 544 个 | 雕刻 63、他的形态键组合 12、左右拆分 4、20% 的口型 15。他的形态键一个都不删。 |
| 舌头 10 个姿势 | 上、下、左右、斜向、卷舌。每个都是完整的伸舌姿势，混合也不会走样。 |
| 包 3.0 MB | 只有形态差异，不含模型数据。 |

### 内容

- 场景内校准和 7 个微调旋钮。
- 调试面板：实时显示脸、眼睛和所有表情的数值。左手腕的按钮可开关。
- 平滑 关闭 / 5 到 30 ms，或 Stop Motion。别人看到的和你设置的一样。
- 定格和瞳孔 (模拟或追踪器)。
- 4 个表情 (闪亮眼、脸红、汗滴、阴郁)：由你的表情触发，每个都有自己的菜单开关。
- 任何张嘴程度下嘴都能干净地闭合：嘴唇不会互相挤压，嘴角也不会出现黑色褶痕。
- 灵动的眼睛：别人能看到细微自然的眼球跳动。0 bit。

### 模型上的变化

- 面部和眼睛交给面捕，所以他的手动眼睛控制菜单会被移除。
- 手势表情默认关闭 (菜单开关)。
- Makeup：_FT 副本上的脸部滑块会恢复默认，原模型保持不变。
- 其他一切保持原样。

### 缺点

- 仅限 Yuri (Cold、Warm、Kisekae、Makeup)。 已在 PC 上测试，Quest 未测试。
- 校准和 Tune 会保存，但重置模型会恢复默认值。
- 印地语和阿拉伯语仅有校准面板，菜单和补丁工具显示英文。
- 如果 Yuri 更新改变了脸部网格，需要对应的新版本。

### 需要

Yuri (任意版本)、VRChat SDK (3.10.6 或更新)、VRCFT (Steam 版，main 或 beta 分支均可)，以及支持 VRCFT (Unified Expressions) 的面捕设备。 Yuri 本体 (Modular Avatar、lilToon) 请按 VISIONTOKYO 的说明操作。

### 技术细节

- 开销的测量方法：在 Unity 中比较模型自身的 FX 和完成后的 FX，取重复 10 帧运行的中位数。原生于 2026-11-20 在干净的场景中测得，当天编辑器误差约 30%。
- 脸部网格 13,384 顶点 / 23,004 三角形。
- 眼睛：VRChat 把眼睛肌肉限制在 1，所以副本有自己的 humanoid，眼睛活动范围和 VRChat 视线角度都更大。
- 闭嘴形态键的上限取决于下巴张开的程度，法线正好抵消下巴的部分，光影也不会乱。
- 平滑不受帧率影响，你的预设用 3 bit 同步。Stop Motion 是预设的一个值，不额外占用。
- 原生：140 条表达式指令，325 次面捕运算。

---

> **Mustard Awards**  
> **Yuri: 7.5 / 10 mustard cans.**  
> How well the model behaved on the way to face tracking. Higher is better.  
> Plus: 544 shapes to build from, and his own sparkle, blush, sweat and shadow decals, ready to become emotes.  
> Minus: his eyes barely turned out of the box, and his jaw shapes didn't close cleanly.

## 调试面板

![debug panel](debug_panel.png)
