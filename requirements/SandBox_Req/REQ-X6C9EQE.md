---
id: REQ-X6C9EQE
type: software-requirement
title: User account service synchronises the room temperature
status: Draft
priority: Medium
owner: M. Farouk
tags:
  - customer-request
former-id: SW-ZXQK87
parent: REQ-PEF0WVS
order: a1
links:
  - type: refines
    target: REQ-PEF0WVS
    confirmed: 08f38a1d34b8
---
The OTA server shall log audit records with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly for at least 10 years
- No error entries in the device log
