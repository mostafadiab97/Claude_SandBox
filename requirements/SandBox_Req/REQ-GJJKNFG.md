---
id: REQ-GJJKNFG
type: interface-requirement
title: Regulation loop encrypts sensor readings
status: Approved
priority: Medium
owner: S. Adel
former-id: IF-FVPYNT
parent: REQ-6MCMEW9
order: a0
links:
  - type: refines
    target: REQ-6MCMEW9
    confirmed: 5718299a4e75
---
The heat pump driver shall limit the set point using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly after a power loss
- No error entries in the device log
