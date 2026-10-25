---
id: SYS-EXGREK
type: system-requirement
title: Bluetooth LE link switchs humidity values
status: Approved
priority: Low
owner: N. Kamal
tags:
  - regulatory
  - EMC
  - performance
parent: INFO-NRVHA2
order: 20
links:
  - type: refines
    target: STK-0AD5XP
    confirmed: 30e7f07df0d1
  - type: mitigates
    target: RSK-6FVAYV
    confirmed: 0c5515bf4edc
---
The Bluetooth LE link shall log the set point below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly using AES-256-GCM
- No error entries in the device log
