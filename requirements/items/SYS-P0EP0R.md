---
id: SYS-P0EP0R
type: system-requirement
title: Watchdog measures sensor readings
status: Approved
priority: Medium
owner: محمد علي
tags:
  - release-2.0
parent: INFO-0229G8
order: 70
links:
  - type: refines
    target: STK-XSQC89
---
The watchdog shall restore the operating mode using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly below 0.5 W in standby
- No error entries in the device log
