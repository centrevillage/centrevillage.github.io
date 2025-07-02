---
layout: product
title: "SxS"
name: "SxS"
image: SxS.png
tags:
 - Sequencer
price: "19,800 JPY"
consumption: "25mA (+12V) / 10mA (-12V) / 5mA (+5V)"
hp: 4
deep: 26
date: 2024-07-27
active: true
publish: true
---

# Digital Controlled Analog Sequencer

Available at the japanese stores:

[Clockface Modular](https://clockfacemodular.com/products/centrevillage-sxs)

[Five G](https://fiveg.net/?pid=181835582)

[centrevillage synth store](https://centrevillage.stores.jp/items/66ad8831bb97772013b536ee)

## English

SxS is a 6-step digital controlled analog sequencer.
The CV output path is fully analog and step switching is digitally controlled.

The output CV and the trigger output ON/OFF can be set for each step, and the running direction of the step can be changed to reverse/stop/forward using a 3-point toggle switch.

You can also enter Active Step mode by tapping the MODE button.
(The ACT LED lights red)

In Active Step mode, each step can be enabled/disabled, and disabled steps will be skipped during step progression.
Tap the MODE button again to return to Trig mode.

Furthermore, by holding down the MODE button and pressing the step button, you can divide the steps into A/B groups.

The position of the pressed STEP button becomes the end position of group A, and the next step becomes the start position of group B.
(To cancel group division, hold down the MODE button and press the 6th STEP button)

The steps in group A progress each time a clock is input, and the steps in group B progress one step each time the steps in group A complete one cycle.
If you divide the steps into groups, the output value of CV will be half of the sum of the values ​​of group A and group B:

・When there is no group division

CV Out  =  Group A CV

・When dividing into groups

CV Out  =  (Group A CV + Group B CV)  / 2

By group division, 6 steps can be divided into 2x4, 3x3, etc., making it possible to use it as a pseudo 8-step or 9-step sequencer.

In addition, it is possible to use different group division methods and change the sequence running mode.
Details will be explained the manual.

 [Manual](https://docs.google.com/document/d/1AumPKeIKoL44SH7que2D2wKOI5kRUtmTZuQ4kaXP_RI/edit?usp=sharing)

**firmware:**

[firmware ver1.1](https://drive.google.com/file/d/1T92VHnZxhYYHRbjwIzcpGq3KAc1149De/view?usp=sharing)

- Fixed a bug where the trigger output could remain high when sequence stopped if the reset input is used.


## 日本語

SxSは6ステップのデジタル制御アナログシーケンサーです。
CV出力のパスは完全にアナログで、ステップの切り替えはデジタル制御されます。

ステップごとに出力CV値の設定、およびトリガー出力のON/OFFを設定することができ、ステップの走行方向は3ポイントのトグルスイッチによって逆転/停止/正転に変更することができます。

また、MODEボタンをタップすることで、Active Stepモードに入ることができます。
(ACT LEDが赤点灯)
Active Stepモードでは、ステップごとに有効/無効を設定することができ、無効化されたステップはステップ進行時にスキップされます。
MODEボタンを再度タップするとTRIG入力モードに戻ります。

更に、MODEボタンを押しながらステップボタンを押すことで、ステップをA/Bグループに分割することができます。
押したステップボタンの位置が、Aグループの終わりの位置になり、その次のステップがBグループの開始位置になります。
(グループ分割を解除する場合は、MODEボタンを押しながら、 6ステップ目のボタンを押します)

Aグループのステップはクロック入力のたびに進行し、BグループのステップはAグループのステップが一周したときに一つ進行します。
ステップをグループに分割した場合、CVの出力値はAグループとBグループの値の平均値になります:

・グループ分割無し

CV Out  =  Group A CV

・グループ分割時

CV Out  =  (Group A CV + Group B CV)  / 2

グループ分割によって、 6つのステップを 2x4や3x3などに分割することができ、疑似的に8ステップや9ステップのシーケンサーとして使うことが可能です。

その他、異なるグループ分割の方法や、走行モードの変更などが可能です。
詳細はマニュアルをご参照ください。

[マニュアル](https://docs.google.com/document/d/1lc6U96vIkQRXBdtkJ8WgugAilq6yz7U1puORhqo6XZ8/edit?usp=sharing)

**ファームウェア:**

[firmware ver1.1](https://drive.google.com/file/d/1T92VHnZxhYYHRbjwIzcpGq3KAc1149De/view?usp=sharing)

- リセット入力を使用している場合に、シーケンスが停止した際にトリガー出力がHigh状態のままになってしまうことがあるバグを修正

