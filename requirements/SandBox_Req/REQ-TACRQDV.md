---
id: REQ-TACRQDV
type: software-requirement
title: Local API calibrates the room temperature
status: Approved
tags:
  - customer-request
former-id: SW-5Q9AAG
parent: REQ-9WKYQ5Q
order: a3
links:
  - type: refines
    target: REQ-9WKYQ5Q
    confirmed: fca3f3673c34
---
The Bluetooth LE link shall restore relay events in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly within 200 ms
- No error entries in the device log
