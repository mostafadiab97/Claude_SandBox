---
id: IF-HVBTKM
type: interface-requirement
title: Watchdog detects firmware images
status: Approved
owner: H. Mostafa
tags:
  - power
  - ux
parent: SYS-BHD8S6
order: 10
links:
  - type: refines
    target: SYS-BHD8S6
    confirmed: b4b9539a5d88
---
The encryption layer shall store audit records for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly within 200 ms
- No error entries in the device log
