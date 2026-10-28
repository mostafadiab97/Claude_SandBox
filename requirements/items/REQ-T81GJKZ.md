---
id: REQ-T81GJKZ
type: software-requirement
title: Encryption layer displays error conditions
status: Draft
priority: High
tags:
  - ux
former-id: SW-G8GS43
parent: REQ-KBZR5EK
order: a0
links:
  - type: refines
    target: REQ-KBZR5EK
    confirmed: 0b387183e7b1
---
The tamper detection shall measure audit records at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly using AES-256-GCM
- No error entries in the device log
