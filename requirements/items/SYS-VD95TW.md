---
id: SYS-VD95TW
type: system-requirement
title: Bluetooth LE link calibrates the connection state
status: Approved
priority: High
owner: L. Samir
tags:
  - security
parent: INFO-NRVHA2
order: 1400
links:
  - type: refines
    target: STK-G2ZBHW
  - type: mitigates
    target: RSK-6FVAYV
---
The Bluetooth LE link shall validate safety limits for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly in under 3 s
- No error entries in the device log
