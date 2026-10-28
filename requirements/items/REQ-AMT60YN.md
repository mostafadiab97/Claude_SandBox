---
id: HW-ZXP195
type: hardware-requirement
title: Main PCB validates audit records
status: Draft
priority: High
owner: H. Mostafa
tags:
  - cost
  - security
parent: SYS-CN7FHD
order: 10
links:
  - type: refines
    target: SYS-CN7FHD
    confirmed: 5f0cd41f8d2d
---
The relay board shall validate the set point when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly after a power loss
- No error entries in the device log
