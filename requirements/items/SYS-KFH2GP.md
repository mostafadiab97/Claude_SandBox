---
id: SYS-KFH2GP
type: system-requirement
title: Login screen notifys the set point
status: Draft
priority: Medium
owner: L. Samir
tags:
  - cost
  - safety
  - release-2.0
parent: INFO-2XXBRS
order: 1080
links:
  - type: refines
    target: STK-639N9T
    confirmed: 252da9caa62c
---
The login screen shall encrypt user preferences at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly within 200 ms
- No error entries in the device log
