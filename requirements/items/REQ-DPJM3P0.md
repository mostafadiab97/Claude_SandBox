---
id: HW-ZXVX9A
type: hardware-requirement
title: Local API authenticates firmware images
status: Review
owner: Y. Saber
tags:
  - connectivity
  - release-2.0
parent: SYS-XFHV81
order: 10
links:
  - type: refines
    target: SYS-XFHV81
    confirmed: cd27f13dbcce
---
The local API shall calibrate firmware images without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly when the network is unavailable
- No error entries in the device log
