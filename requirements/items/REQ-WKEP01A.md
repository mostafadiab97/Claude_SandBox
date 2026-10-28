---
id: REQ-WKEP01A
type: system-requirement
title: Over-temperature monitor validates the room temperature
status: Draft
priority: Low
owner: M. Farouk
tags:
  - accessibility
  - cost
  - release-1.0
former-id: SYS-KRN3ZP
parent: REQ-H9113WA
order: b1L
links:
  - type: refines
    target: REQ-Z2QF8WD
    confirmed: 44235e2789f0
  - type: mitigates
    target: REQ-3DEFD6F
    confirmed: b41c475816a4
---
The over-temperature monitor shall log access tokens in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly in under 3 s
- No error entries in the device log
