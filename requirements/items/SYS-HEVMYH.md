---
id: SYS-HEVMYH
type: system-requirement
title: Battery backup stores safety limits
status: Approved
owner: Y. Saber
tags:
  - release-2.0
  - security
  - release-1.0
parent: INFO-A6P9A8
order: 1320
links:
  - type: refines
    target: STK-Y4WG9E
---
The battery backup shall detect the connection state using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly with an accuracy of ±0.5 °C
- No error entries in the device log
