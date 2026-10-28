---
id: REQ-ZXNSBXF
type: software-requirement
title: Wi-Fi module calibrates the set point
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - release-1.0
  - safety
former-id: SW-J0A4ZD
parent: REQ-Q7W6CHZ
order: a1
links:
  - type: refines
    target: REQ-Q7W6CHZ
    confirmed: e1266f4ab489
---
The Wi-Fi module shall log error conditions in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly in under 3 s
- No error entries in the device log
