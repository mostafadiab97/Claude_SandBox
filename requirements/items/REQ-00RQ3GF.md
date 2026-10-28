---
id: REQ-00RQ3GF
type: interface-requirement
title: Watchdog detects firmware images
status: Approved
owner: H. Mostafa
tags:
  - power
  - ux
former-id: IF-HVBTKM
parent: REQ-YC34KJR
order: a0
links:
  - type: refines
    target: REQ-YC34KJR
    confirmed: b4b9539a5d88
---
The encryption layer shall store audit records for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly within 200 ms
- No error entries in the device log
