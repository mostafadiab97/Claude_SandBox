---
id: REQ-AYEYNHE
type: hardware-requirement
title: Menu system validates the room temperature
status: Draft
priority: Low
owner: É. Laurent
tags:
  - connectivity
former-id: HW-1FPJKB
parent: REQ-B5QM2ZG
order: a1
links:
  - type: refines
    target: REQ-B5QM2ZG
    confirmed: 02e3c6ed2cec
---
The menu system shall calibrate relay events using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly in under 3 s
- No error entries in the device log
