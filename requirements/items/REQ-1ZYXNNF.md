---
id: REQ-1ZYXNNF
type: system-requirement
title: Login screen notifys the set point
status: Draft
priority: Medium
owner: L. Samir
tags:
  - cost
  - safety
  - release-2.0
former-id: SYS-KFH2GP
parent: REQ-QYXGSQ4
order: b0j
links:
  - type: refines
    target: REQ-EMZ19WQ
    confirmed: 252da9caa62c
---
The login screen shall encrypt user preferences at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly within 200 ms
- No error entries in the device log
