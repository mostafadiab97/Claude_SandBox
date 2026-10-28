---
id: SYS-KRN3ZP
type: system-requirement
title: Over-temperature monitor validates the room temperature
status: Draft
priority: Low
owner: M. Farouk
tags:
  - accessibility
  - cost
  - release-1.0
parent: INFO-0229G8
order: 1460
links:
  - type: refines
    target: STK-SM9B7Z
    confirmed: 44235e2789f0
  - type: mitigates
    target: RSK-4WN2DG
    confirmed: b41c475816a4
---
The over-temperature monitor shall log access tokens in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly in under 3 s
- No error entries in the device log
