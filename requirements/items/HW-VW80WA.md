---
id: HW-VW80WA
type: hardware-requirement
title: Encrypt the set point — detail
status: Approved
priority: High
owner: A. Hassan
parent: HW-0C67M1
order: 10
links:
  - type: refines
    target: HW-0C67M1
    confirmed: bc43b8bf2879
---
The battery backup shall log firmware images using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly within 200 ms
- No error entries in the device log
