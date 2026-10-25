---
id: HW-2Z6C9V
type: hardware-requirement
title: User account service authenticates the connection state
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - i18n
  - safety
parent: SYS-KCC5WV
order: 20
links:
  - type: refines
    target: SYS-KCC5WV
    confirmed: 201bc4a0f987
---
The user account service shall validate access tokens with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly within 200 ms
- No error entries in the device log
