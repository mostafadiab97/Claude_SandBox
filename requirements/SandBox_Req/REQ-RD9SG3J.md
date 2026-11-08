---
id: REQ-RD9SG3J
type: system-requirement
title: Heating controller displays the set point
status: Obsolete
priority: Medium
owner: É. Laurent
tags:
  - release-1.0
  - regulatory
former-id: SYS-SDM6X9
parent: REQ-7ED7ZET
order: b0U
links:
  - type: refines
    target: REQ-S4C7PYC
    confirmed: d92faafa8cce
  - type: mitigates
    target: REQ-95C6RSR
    confirmed: 84e686f1bbcc
---
The heating controller shall encrypt user preferences in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly within 200 ms
- No error entries in the device log
