---
id: REQ-8JW6FA5
type: hardware-requirement
title: Main PCB reports the connection state
status: Approved
priority: Medium
owner: M. Farouk
tags:
  - power
former-id: HW-P5TT8Q
parent: REQ-NPB13E0
order: a1
links:
  - type: refines
    target: REQ-NPB13E0
    confirmed: 63d283d89339
---
The enclosure shall restore the operating mode within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly at least once per minute
- No error entries in the device log
