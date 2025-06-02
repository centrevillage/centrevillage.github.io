---
layout: product
title: "Trigger HaCker"
name: "Trigger HaCker"
image: TriggerHaCker.png
tags:
 - Sequencer
 - Trigger
price: "38,000 JPY"
consumption: "50mA (+12V) / 25mA (-12V) / 0mA (+5V)"
hp: 12
deep: 36
date: 2018-07-01
active: false
---

5x5 matrix trigger sequencer.

[store](https://centrevillage.stores.jp/items/61600e4aa1027512240c1d80)

See more detail:

[Trigger HaCker Manual (日本語)](https://docs.google.com/document/d/1wfTpOyFKQlBgTaDxopgiGIcWkLXFvFyb3FhJBAJs8G0/edit?usp=sharing)

### Firmware
[ver 1.2.2](https://drive.google.com/file/d/11zpDe8KvET-Zd7j3KJihuKZKEJypOX7i/view?usp=sharing)

- bugfix: clock divide&delay setting is loaded at wrong value when power on.
- bugfix: clock modulation is not working when track group used.


[ver 1.2.0](https://drive.google.com/open?id=1UA47syRsT1LW-bYp02yv5mcMHAwxENdi)

- Add step probability
- Change quick track change behavior
- Add clear & randomize function (Track+Mode)
- Add run mode for pattern chain

[ver 1.1.1](https://drive.google.com/open?id=1ozafKr6kfSMEf9f4M1Avepzz9d-8Bnu2)

- bugfix: weird step change from first step to next step with clock div >= 2

[ver 1.1.0](https://drive.google.com/open?id=19Huk-8nMR4OwdQEMxaEloKDS9AWT-TVK)

- Add "Clock Mod" mode
- Reduce clock jitter in case of external trigger sync

[ver 1.0.3](https://drive.google.com/open?id=1qzCdWlfMMj83pX2ZluKY4W4s84WW1PPc)

- Change sequence reset behavior (current pattern is reset when sequence is reset)
- Fix various display problem

[ver 1.0.2](https://drive.google.com/open?id=1kHF_RdrpS1UD8aG8NgoIk1VqlJRV_C81)

- Fix various midi sync problem
- bugfix: Ignore step toggle in case of toggling track mute

[ver 1.0.1](https://drive.google.com/file/d/1vQdAl0LDxYtnBYmgptWp9vPy2t38G1UN/view?usp=sharing)

- Fix cv offset (0.7V to 0V)
- Display version in case of TAP button pressing and power on
