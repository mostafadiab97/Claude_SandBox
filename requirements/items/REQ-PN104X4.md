---
id: REQ-PN104X4
type: interface-requirement
title: Encryption layer logs sensor readings
status: Approved
priority: Medium
owner: É. Laurent
former-id: IF-50TCDX
parent: REQ-33MFB68
order: a0
links:
  - type: refines
    target: REQ-33MFB68
    confirmed: 81a097bb4f90
---
The watchdog shall switch schedule entries below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly when the network is unavailable
- No error entries in the device log
