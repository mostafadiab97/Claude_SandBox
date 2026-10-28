---
id: REQ-3W441VR
type: hardware-requirement
title: Encrypt the set point — detail
status: Approved
priority: High
owner: A. Hassan
former-id: HW-VW80WA
parent: REQ-M95A6SS
order: a0
links:
  - type: refines
    target: REQ-M95A6SS
    confirmed: bc43b8bf2879
---
The battery backup shall log firmware images using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly within 200 ms
- No error entries in the device log
