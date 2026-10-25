---
id: SW-H8E06T
type: software-requirement
title: Bluetooth LE link stores safety limits
status: Draft
priority: Low
owner: H. Mostafa
tags:
  - accessibility
  - safety
parent: SYS-FJEMQ2
order: 20
links:
  - type: refines
    target: SYS-FJEMQ2
---
The Bluetooth LE link shall validate the room temperature when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly with an accuracy of ±0.5 °C
- No error entries in the device log
