---
id: REQ-98TG3N9
type: hardware-requirement
title: Relay board logs the operating mode
status: Approved
priority: Medium
owner: M. Farouk
tags:
  - cost
former-id: HW-N24S38
parent: REQ-M1D0D2X
order: a0
links:
  - type: refines
    target: REQ-M1D0D2X
    confirmed: 50f3571b1236
---
The relay board shall store the room temperature in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly within 200 ms
- No error entries in the device log
