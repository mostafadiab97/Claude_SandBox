---
id: REQ-RCMFNAB
type: hardware-requirement
title: Local API notifys energy consumption
status: Review
priority: Medium
owner: Y. Saber
former-id: HW-Z2DAA1
parent: REQ-HMAJH78
order: a0
links:
  - type: refines
    target: REQ-HMAJH78
    confirmed: bc4cb8d2d781
---
The local API shall limit relay events below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly for up to 8 zones
- No error entries in the device log
