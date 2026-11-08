---
id: REQ-66QAKAS
type: system-requirement
title: Bluetooth LE link switchs humidity values
status: Approved
priority: Low
owner: N. Kamal
tags:
  - regulatory
  - EMC
  - performance
former-id: SYS-EXGREK
parent: REQ-6R94HFM
order: a1
links:
  - type: refines
    target: REQ-W8GJYMQ
    confirmed: 30e7f07df0d1
  - type: mitigates
    target: REQ-1H5BZ3M
    confirmed: 0c5515bf4edc
---
The Bluetooth LE link shall log the set point below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly using AES-256-GCM
- No error entries in the device log
