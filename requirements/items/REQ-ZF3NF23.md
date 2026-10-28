---
id: REQ-ZF3NF23
type: hardware-requirement
title: Tamper detection switchs access tokens
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - release-1.0
  - performance
former-id: HW-W0ZHZF
parent: REQ-JEP1255
order: a2
links:
  - type: refines
    target: REQ-JEP1255
    confirmed: 5ee18259fea5
---
The secure boot shall switch user preferences in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly after a power loss
- No error entries in the device log
