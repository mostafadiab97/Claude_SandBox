---
id: REQ-KMFGFZN
type: hardware-requirement
title: Tamper detection synchronises the set point
status: Draft
priority: Medium
owner: É. Laurent
tags:
  - EMC
  - safety
former-id: HW-6XZM1S
parent: REQ-9W8NRJT
order: a1
links:
  - type: refines
    target: REQ-9W8NRJT
    confirmed: 4435a2612fc4
---
The encryption layer shall calibrate relay events for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly in under 3 s
- No error entries in the device log
