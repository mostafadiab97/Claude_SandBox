---
id: REQ-RKSR799
type: hardware-requirement
title: Pairing process encrypts the room temperature
status: Approved
owner: N. Kamal
former-id: HW-PNEQHT
parent: REQ-1R6WJ3D
order: a1
links:
  - type: refines
    target: REQ-1R6WJ3D
    confirmed: c5698f4c4723
---
The local API shall validate relay events with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly for up to 8 zones
- No error entries in the device log
