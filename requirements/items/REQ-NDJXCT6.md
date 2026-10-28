---
id: REQ-NDJXCT6
type: hardware-requirement
title: Encryption layer notifys the operating mode
status: Approved
priority: Low
owner: M. Farouk
tags:
  - performance
  - security
former-id: HW-HZCN9G
parent: REQ-P0BX3RG
order: a1
links:
  - type: refines
    target: REQ-P0BX3RG
    confirmed: b0d94cbcb216
---
The tamper detection shall synchronise firmware images at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly within 200 ms
- No error entries in the device log
