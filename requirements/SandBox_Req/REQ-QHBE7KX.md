---
id: REQ-QHBE7KX
type: system-requirement
title: Mobile app measures access tokens
status: Review
priority: High
owner: R. Nabil
tags:
  - security
  - safety
former-id: SYS-M63JNN
parent: REQ-QYXGSQ4
order: b1v
links:
  - type: refines
    target: REQ-5P7JDVE
    confirmed: 4a1d76b1da2c
  - type: mitigates
    target: REQ-1CKR5QB
    confirmed: ce36fe2999cf
---
The mobile app shall display the room temperature when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly with an accuracy of ±0.5 °C
- No error entries in the device log
