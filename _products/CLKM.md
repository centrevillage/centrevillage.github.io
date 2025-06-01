---
layout: product
title: "CLKM"
name: "CLKM"
image: CLKM.png
tags:
 - MIDI
 - Clock
price: "14,300 JPY"
consumption: "25mA (+12V) / 0mA (-12V) / 0mA (+5V)"
hp: 2
deep: 36
date: 2022-02-23
---

# Compact Clock Master

#### This module is available only at [Official Store](https://centrevillage.stores.jp/).

### English 

CLKM is an ultra compact clock master with just 2hp.

It is not only starting itself, but also receiving midi transport messages (that is START/STOP/CLOCK).

That tempo can be set by tapping the TAP button or clicking the “+” or “-” buttons.

Also, CLKM can change the clocks per beat, the swing and the reset timing.

#### See more detail on this [MANUAL](https://docs.google.com/document/d/1U_xy5FC0thGT-O4X2dIkm-sbkyI0ILSph1olU1p-DHw/edit?usp=sharing)

---
firmware:

[v1.8](https://drive.google.com/file/d/15M8Fad0XpwsCEGB1HZNaThQTUZvMre1R/view?usp=drive_link)

- Fixed an issue where the clock output would be skipped in rare cases when used as a master clock.

[v1.7](https://drive.google.com/file/d/1PAw8Xtyf-69eTki8RQlERsmy0syCBqF1/view?usp=drive_link)

- add a Clock Behavior setting. (b S/o)

[v1.6](https://drive.google.com/file/d/14pIosncx2SHmxtwmiuOwu3oTJzqjd4qr/view?usp=sharing)

- add a new reset timing config (r U).

[v1.5](https://drive.google.com/file/d/1whxqOy1YnHHZZsTcFgQ4_OPYHyIcNWxG/view?usp=sharing)

 - add a 24 clock per beat (24ppqn) setting.

[v1.4](https://drive.google.com/file/d/1c6WdPVftzipx8R617lHOFXu8CkxOk_5s/view?usp=sharing)

 - fix the BPM estimation problem.
 - fix midi receive instability because of missing the rx interrupt sometime.

### 日本語

CLKM はわずか2HPのコンパクトなクロックマスターモジュールです。

単に自走するだけではなく、MIDIトランスポートメッセージ（START/STOP/CLOCK）を受信することができます。

テンポは、”TAP”ボタンによるタップテンポ、あるいは”+”または”-”ボタンを押すことで設定できます。

また、CLKM では１拍あたりのクロック数やスイング、リセットタイミングの設定ができます。

#### 詳しくは[マニュアル](https://docs.google.com/document/d/1hHRl4Am7PbmwSQGi8kQQ8gf6ktl0BkJiXs7NqKsQ47U/edit?usp=sharing)をご参照ください。

---
firmware:

[v1.8](https://drive.google.com/file/d/15M8Fad0XpwsCEGB1HZNaThQTUZvMre1R/view?usp=drive_link)

- マスタークロックとして利用する場合にごく稀にクロック出力がスキップされる問題の解決

[v1.7](https://drive.google.com/file/d/1PAw8Xtyf-69eTki8RQlERsmy0syCBqF1/view?usp=drive_link)

- クロック挙動設定を追加 (b S/o)

[v1.6](https://drive.google.com/file/d/14pIosncx2SHmxtwmiuOwu3oTJzqjd4qr/view?usp=sharing)

- 新しいリセットタイミング設定を追加 (r U)

[v1.5](https://drive.google.com/file/d/1whxqOy1YnHHZZsTcFgQ4_OPYHyIcNWxG/view?usp=sharing)

 - Clock Per Beat 設定に 24 を追加

[v1.4](https://drive.google.com/file/d/1c6WdPVftzipx8R617lHOFXu8CkxOk_5s/view?usp=sharing)

 - 外部同期時のBPM推定が時々おかしくなる問題を修正
 - まれにMIDI受信割り込みが発生せず、MIDI受信が不安定になる問題を修正

