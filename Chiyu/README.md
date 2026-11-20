<img src="icon.png" width="160" align="right">

# Chiyu Face Tracking v2.0.0-native


Free report. Read this before you buy: what you get, what changes on your avatar, and the numbers, explained.
Face tracking for **ちゆ - Chiyu** by plium. Built by mustar.

Chiyu: [ちゆ - Chiyu by plium](https://booth.pm/en/items/8942824)

Demo video: [https://youtu.be/25gfjd5u3mI](https://youtu.be/25gfjd5u3mI)

> **Mustard Awards**
> **Chiyu: 8.5 / 10 mustard cans.**
> How well the model behaved on the way to face tracking. Higher is better.
> Plus: near seamless. 1,133 shapes with clean left/right splits, real eye bones, and a tidy, well-built face mesh that stayed identical from pre-release to launch.
> Minus: her tongue could have more verts.



---

[日本語](#日本語) · [English](#english)

## 日本語

### 概要

- ちゆの口、目、舌、頬、眉があなたの顔に合わせて動きます。彼女のために作ったシェイプ 67 個。
- 本物のアイボーンで視線が動き、外側 28°、内側 22°、上下 14°。
- アニメモード: 顔がポーズを保ち 1 秒に 8 回切り替わり、口は声に合わせてパキッと動きます。
- ボタンひとつで導入。元のファイルには触りません。
- ちゆ本体とフェイストラッキング機器は含まれません。

ちゆには plium さんのフェイストラッキングも付属しています。mFT は、より幅広いツールと豊かな表現力を求める人のための選択肢です。

### 数字とその意味

| 数字 | 意味 |
|---|---|
| 自分 +0.28 ms、他の人 +0.27 ms (ネイティブ) | 1 フレームあたりの追加負荷。従来版は自分 +0.33 ms、他の人 +0.33 ms。彼女自身の FX は約 0.22 ms。 |
| 220 / 256 (ネイティブ)、253 / 256 (従来版) | 同期パラメーター。ネイティブ: 彼女自身の 181 + 追加機能 39 (Full) または 10 (Light、合計 191)。顔の動き自体は 0 bit。 |
| シェイプ 84 個 + 彼女の 1,133 個 | 67 個は FT 用、15 個はビゼーム 35%、2 個は瞳。彼女のシェイプは 1 つも消しません。 |
| 舌 10 ポーズ | 上下左右、斜め、丸め。舌出しは 4 段階で伸びます。 |
| パッケージ 2.4 MB | 差分データのみ。アバター本体のデータは入っていません。 |

### 中身

- ワールド内キャリブレーションと微調整ダイヤル 7 種。
- デバッグパネル: 顔、目、全表情の値をその場で表示。左手首のボタンで開閉。
- スムージング Off / 5〜30 ms、または Stop Motion。設定は見ている人にも同じに映ります。
- FT anime visemes: 声で口がパキッと切り替わり、トラッキングの口に重なります。
- 表情キープ (Freeze)、瞳 (エミュレート / トラッカー)、目が表情に反応 (笑顔、にらみ、下を見る)。
- エモート 11 種 (ネイティブ): 猫目、うるうる、キラキラ、涙、青ざめ、白目、ショック、ほっぺ、照れ、ぐるぐる、ハート。
- PaperTrackerMode: Paper Tracker でファンネルとパッカーが同時に出るとき、強い方だけを使います。

### アバターで変わること

- Gimmick > Face は外れ、もぐもぐ 2 種とナデナデは Extras > Emotes_Vendors に移ります。
- 彼女の自動まばたきは視線トラッキング中は止まり、切ると戻ります。頭なで顔と AFK はそのままです。
- ハンドジェスチャーの表情は初期 OFF (メニューで ON)。
- リップシンクはコピー側で私のレイヤーが動かします。アンインストールで元に戻ります。
- 衣装、髪、小物のメニューはそのまま使えます。

### 弱点

- ちゆ専用。PC で確認、Quest は未検証。
- 従来版は枠に収めるため、Standing / Crouching / Prone / Floating のポーズ切替とエモートが入りません。Breast_Size と Mogumogu_Type は 5 段階になります。ネイティブは全部入ります。
- キャリブレーションと Tune は保存されますが、アバターのリセットでは初期値に戻ります。
- ちゆの更新で顔のメッシュが変わると、対応版が必要です。

### 必要なもの

ちゆ、VRChat SDK (3.10.6 以降)、VRCFT、VRCFT (Unified Expressions) で動くフェイストラッカー。ちゆ本体の導入は plium さんの説明書に従ってください (Modular Avatar、lilToon)。

### 技術的な詳細

- 負荷の測り方: Unity 上で彼女の FX と完成した FX を比較、10 フレームの実行を繰り返した最速値 (2026-11-03)。誤差は約 15%。
- 顔メッシュ 12,915 頂点。ちゆ 1.0.0 で確認。
- デルタ法線はゼロ: 彼女のフラットな顔の陰影を崩しません。
- 舌のシェイプは舌だけを動かし、顎と舌が両方上がったときだけ補正が入ります (0 bit)。
- ネイティブの式の命令 325 / 2048。

---

## English

### In short

- Chiyu's mouth, eyes, tongue, cheeks and brows move with your face. 67 shapes built for her.
- Gaze on her real eye bones: 28° outward, 22° inward, 14° up and down.
- An anime mode: the face holds a pose and jumps 8 times a second, and the mouth snaps with your voice.
- One button to install. Your original files are never touched.
- Chiyu and a face tracking device are not included.

Chiyu also comes with plium's own face tracking. mFT is an option for people who want a wider toolkit and more expressiveness.

### The numbers, and what they mean

| number | what it means |
|---|---|
| You +0.28 ms, viewers +0.27 ms (native) | Added per frame. Classic: you +0.33 ms, viewers +0.33 ms. Her own FX is about 0.22 ms. |
| 220 / 256 (native), 253 / 256 (classic) | Synced parameters. Native: her own 181 + extras 39 (Full) or 10 (Light, total 191). The face itself is 0 bits. |
| 84 shapes + her 1,133 | 67 for face tracking, 15 visemes at 35%, 2 for pupils. None of hers removed. |
| 10 tongue poses | Up, down, sideways, diagonals, roll. Tongue out extends in 4 stages. |
| Package 2.4 MB | Shape differences only, no avatar data. |

### What you get

- In-world calibration and 7 fine-tune dials.
- Debug panel: face, eyes and every expression value, live. A button on your left wrist opens it.
- Smoothing Off / 5 to 30 ms, or Stop Motion. Viewers see you as you set it.
- FT anime visemes: the mouth snaps with your voice, on top of tracking.
- Freeze, pupils (emulated or tracker), and eyes that react to your face (smile, glare, looking down).
- 11 emotes (native): cat eyes, teary eyes, sparkle, tears, blue face, white eyes, shock, cheek, blush, dizzy, hearts.
- PaperTrackerMode: when Paper Tracker fires funnel and pucker together, the stronger one wins.

### What changes on your avatar

- Gimmick > Face goes. Mogumogu (both) and NadeNade move to Extras > Emotes_Vendors.
- Her auto-blink pauses while Eye Tracking is on, and comes back when it's off. Headpat face and AFK stay.
- Hand gesture expressions start off (menu toggle).
- Lip sync on the copy runs through my layer. Uninstall puts it back.
- Her outfit, hair and prop menus keep working.

### Cons

- Chiyu only. Tested on PC, Quest is untested.
- To fit, classic leaves out the Standing / Crouching / Prone / Floating pose switches and the emotes, and Breast_Size and Mogumogu_Type become 5 steps. Native has everything.
- Calibration and Tune are saved, but Reset Avatar puts them back to default.
- If a Chiyu update changes her face mesh, an updated version is needed.

### You need

Chiyu, the VRChat SDK (3.10.6 or newer), VRCFT, and a face tracker that works with VRCFT (Unified Expressions). For Chiyu herself, follow plium's manual (Modular Avatar, lilToon).

### Technical details

- How cost was measured: her FX against the built one in Unity, fastest of repeated 10-frame runs (2026-11-03). Noise is about 15%.
- Face mesh 12,915 verts. Checked on Chiyu 1.0.0.
- Zero delta normals, so her flat face shading stays clean.
- Tongue shapes move only the tongue; a small correction fires only when jaw and tongue are both up (0 bits).
- Native: 325 / 2048 expression instructions.

---

## Debug panel

![debug panel](debug_panel.png)

## Expressions

FT シェイプ (0 → 1 → 0)。左右は見ている人から見た向き。 FT shapes, each looping 0 → 1 → 0. Left and right are as you look at the avatar (its own left shows on your right).

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

<details><summary>Brows (3)</summary>

<table>
<tr><td align="center"><img src="expressions/BrowInnerUp.webp" width="200" loading="lazy"><br><sub>BrowInnerUp</sub></td><td align="center"><img src="expressions/Brows_Up.webp" width="200" loading="lazy"><br><sub>BrowInnerUp · BrowOuterUp (left, right)</sub></td><td align="center"><img src="expressions/Brows_DownPinch.webp" width="200" loading="lazy"><br><sub>BrowDown · BrowPinch (left, right)</sub></td></tr>
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
