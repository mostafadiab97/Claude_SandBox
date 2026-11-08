---
id: REQ-X79WZPJ
type: system-requirement
title: Heat pump driver measures firmware images
status: Approved
priority: Medium
owner: R. Nabil
former-id: SYS-3NA7W8
parent: REQ-7ED7ZET
order: b2H
links:
  - type: refines
    target: REQ-HA39PC8
    confirmed: f0954f8ba0a2
  - type: mitigates
    target: REQ-QAQ88MR
    confirmed: d372fc071d5d
---
The heat pump driver shall detect relay events for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly below 0.5 W in standby
- No error entries in the device log
