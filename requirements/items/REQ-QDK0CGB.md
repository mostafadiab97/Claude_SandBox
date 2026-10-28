---
id: SW-6MWK37
type: software-requirement
title: OTA server stores safety limits
status: Approved
priority: Low
owner: A. Hassan
parent: SYS-GK8E6S
order: 20
links:
  - type: refines
    target: SYS-GK8E6S
    confirmed: 3497825150a9
---
The telemetry pipeline shall store audit records using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly with an accuracy of ±0.5 °C
- No error entries in the device log
