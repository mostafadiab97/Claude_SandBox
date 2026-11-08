---
id: REQ-SP8WWTA
type: interface-requirement
title: Tamper detection switchs sensor readings
status: Obsolete
owner: J. Müller
tags:
  - regulatory
  - safety
former-id: IF-BYY19Z
parent: REQ-33MFB68
order: a3
links:
  - type: refines
    target: REQ-33MFB68
    confirmed: 81a097bb4f90
---
The watchdog shall store sensor readings when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly within 200 ms
- No error entries in the device log
