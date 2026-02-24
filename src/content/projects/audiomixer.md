---
title: Audio Mixer Circuit
description: A breadboard audio mixer circuit for future Home Assistant control
pubDate: 2025-9-13
heroImage: ../../assets/audiomixer.JPG
updatedDate: 2025-9-13
---

The living room speaker setup is almost fully controllable through Home Asssistant except adjusting the volumes of the TVs. The goal here is to understand how an audio mixer works in order to build or modify one that can be controlled through Home Assistant. This circuit shows a successful powered single channel audio mixer for standard 3.5mm "headphone jack" inputs and output. The future design calls for an ESP board, PWM controlled logarithmic potentiometers, and rotary encoders allowing the user to control the volumes through Home Assistant or manually turning a knob.

- 2x OP37G op amps
- 2x 10kOhm potentiometers
- Oscilloscope and function generator: ADALM2000 + software