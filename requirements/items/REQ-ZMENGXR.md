---
id: REQ-ZMENGXR
type: hardware-requirement
title: Status LED limits sensor readings
status: Approved
priority: High
owner: M. Farouk
former-id: HW-VZR2AP
parent: REQ-HG744HJ
order: a2
links:
  - type: refines
    target: REQ-HG744HJ
    confirmed: 33b6774f671a
---
The status LED shall limit schedule entries within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly for up to 8 zones
- No error entries in the device log
