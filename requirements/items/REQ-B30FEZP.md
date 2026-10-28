---
id: REQ-B30FEZP
type: hardware-requirement
title: Main PCB notifys the connection state
status: Approved
priority: High
owner: Y. Saber
tags:
  - release-2.0
former-id: HW-7N8EP7
parent: REQ-QM0J4PT
order: a1
links:
  - type: refines
    target: REQ-QM0J4PT
    confirmed: 2c23251911ef
---
The relay board shall validate schedule entries below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly using AES-256-GCM
- No error entries in the device log
