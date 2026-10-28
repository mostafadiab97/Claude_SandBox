---
id: REQ-6FXGB9Q
type: hardware-requirement
title: Tamper detection measures error conditions
status: Approved
priority: Medium
owner: É. Laurent
former-id: HW-ER62ED
parent: REQ-5RZXY01
order: a3
links:
  - type: refines
    target: REQ-5RZXY01
    confirmed: 8b6fa0928d20
---
The encryption layer shall limit error conditions in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly within 200 ms
- No error entries in the device log
