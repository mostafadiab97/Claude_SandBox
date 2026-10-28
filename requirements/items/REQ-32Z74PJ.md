---
id: REQ-32Z74PJ
type: software-requirement
title: Encryption layer displays sensor readings
status: Approved
priority: Medium
owner: R. Nabil
former-id: SW-G54R8V
parent: REQ-WN9V1AY
order: a3
links:
  - type: refines
    target: REQ-WN9V1AY
    confirmed: 947f4568b2cf
---
The encryption layer shall measure the room temperature when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly in under 3 s
- No error entries in the device log
