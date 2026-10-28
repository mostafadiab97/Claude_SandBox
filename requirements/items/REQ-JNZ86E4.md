---
id: REQ-JNZ86E4
type: software-requirement
title: OTA server notifys the room temperature
status: Review
priority: High
tags:
  - i18n
  - customer-request
former-id: SW-NTME8A
parent: REQ-H1HVVK4
order: a2
links:
  - type: refines
    target: REQ-H1HVVK4
    confirmed: 76300eb27743
---
The device registry shall store sensor readings within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly at least once per minute
- No error entries in the device log
