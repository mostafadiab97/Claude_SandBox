---
id: REQ-90MCNCR
type: software-requirement
title: Restore error conditions — detail
status: Approved
priority: Low
owner: M. Farouk
tags:
  - safety
former-id: SW-PBCS94
parent: REQ-BPW5VFY
order: a0
links:
  - type: refines
    target: REQ-BPW5VFY
    confirmed: 2c0f1742743a
---
The encryption layer shall report access tokens when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly without user interaction
- No error entries in the device log
