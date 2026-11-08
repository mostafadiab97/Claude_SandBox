---
id: REQ-QDK0CGB
type: software-requirement
title: OTA server stores safety limits
status: Approved
priority: Low
owner: A. Hassan
former-id: SW-6MWK37
parent: REQ-PRHYJ2F
order: a1
links:
  - type: refines
    target: REQ-PRHYJ2F
    confirmed: 3497825150a9
---
The telemetry pipeline shall store audit records using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly with an accuracy of ±0.5 °C
- No error entries in the device log
