---
id: SW-5Q9AAG
type: software-requirement
title: Local API calibrates the room temperature
status: Approved
tags:
  - customer-request
parent: SYS-CY6ETQ
order: 40
links:
  - type: refines
    target: SYS-CY6ETQ
    confirmed: fca3f3673c34
---
The Bluetooth LE link shall restore relay events in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly within 200 ms
- No error entries in the device log
