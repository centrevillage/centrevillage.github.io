---
layout: product
title: "PLLVCO"
name: "PLLVCO"
image: PLLVCO.png
tags:
 - VCO
price: "28,600 JPY"
consumption: "60mA (+12V) / 60mA (-12V) / 0mA (+5V)"
hp: 6
deep: 26
date: 2026-03-20
active: true
publish: true
---

# Phase Locked Loop Oscillator

Available at:

[Clockface Modular](https://clockfacemodular.com/products/centrevillage-pllvco)

## English

**PLLVCO** is a module that combines a **Phase Locked Loop (PLL)** circuit with an analog oscillator.

The oscillator's pitch can be controlled to a rational multiple (N/M) of the frequency of the external oscillator input to the **PLL**.
Additionally, pitch control using a standard V/Oct voltage is also possible.

For example, by controlling the frequency of an internal oscillator to 3/2 times (x 1.5)  the frequency of an externally input oscillator, and then mixing these two oscillators with an external mixer, it is possible to create an oscillator that produces chords overlapping by a perfect fifth.

Furthermore, when an external audio signal is input to the **PLL** input, the pitch of the input audio is detected and output as a V/Oct voltage from the **FRQ** output.
It offers interesting applications, such as inputting vocals or guitar sounds as external audio and controlling the pitch of another, more complex oscillator via the **FRQ** output.
(However, it may not be able to detect input audio that is a chord or has complex harmonics.)

The pitch tracking speed using the PLL circuit can be adjusted with the **SENS** slider.
Furthermore, if tracking is too fast, phase distortion will occur in the waveform, resulting in a tonal change similar to oscillator sync. Therefore, you should normally set the **SENS** speed to a level where phase distortion does not occur.

The frequency range can be set to either a VCO or an LFO, and when set to LFO, it can also be used as a clock-synchronized LFO.
In this case, as with the VCO, it can oscillate at a speed that is a rational number of times the input clock, so it can be used as a clock divider or multiplier.

[Manual](https://docs.google.com/document/d/1BLq3Y0Hr24H9s1kLgD0EaH1suA5PaSRTqkWN019Jvr4/edit?usp=sharing)

## 日本語


**PLLVCO** は **Phase Locked Loop (PLL)** 回路とアナログオシレータを組み合わせたモジュールです。

PLL回路によって、一般的なV/Octによるピッチコントロールだけでなく、**PLL入力**に入力された外部オシレータの有理数倍(N/M倍)の周波数にオシレータのピッチを制御することができます。

これにより、例えば、外部入力されたオシレータの周波数の3/2倍に内部オシレータの周波数をコントロールし、それら二つのオシレータを外部ミキサーでミックスすると、5度で重なる和音のオシレータを実現することができます。

また**PLL入力**に外部音声を入力した場合、入力された音声のピッチが検出され、V/Octの電圧として**FRQ出力**から出力されます。
外部音声として歌声やギター音声を入力し、**FRQ出力**から別のもっと複雑なオシレータのピッチを制御するなど、面白い使い方が可能です。
(ただし、入力音声が和音であったり複雑な倍音を持つ場合にはうまく検出できません）

PLL回路によるピッチトラッキングの速さは**SENSスライダ**によって調整することができます。
また、トラッキングが高速の場合は波形に位相歪みが生じ、オシレータシンクに似た音色の変化が発生するので、通常は位相歪みが生じない程度の速さに**SENS**を設定します。

周波数レンジはVCOかLFOに設定でき、LFOに設定した場合は、クロック同期するLFOとして利用することもできます。
この場合も、VCOの場合と同様に、入力クロックの有理数倍の速度で発振させることができるため、クロックディバイダやマルチプライヤとして使うことができます。

[マニュアル](https://docs.google.com/document/d/1UDBm8DO8My208P_efP59fIJdZE6fqvSqCasaDyewZOo/edit?usp=sharing)
