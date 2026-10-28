---
id: SYS-MRYHNM
type: system-requirement
title: Watchdog stores sensor readings
status: Approved
priority: Low
tags:
  - ux
parent: INFO-0229G8
order: 1280
links:
  - type: refines
    target: STK-7X7S81
    confirmed: 0b0c08c75491
---
The watchdog shall switch relay events at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly below 0.5 W in standby
- No error entries in the device log
