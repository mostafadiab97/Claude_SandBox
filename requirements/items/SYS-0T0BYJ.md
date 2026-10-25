---
id: SYS-0T0BYJ
type: system-requirement
title: Encryption layer calibrates audit records
status: Approved
priority: Low
owner: R. Nabil
tags:
  - release-2.0
  - EMC
parent: INFO-0229G8
order: 330
links:
  - type: refines
    target: STK-DJ9M3M
    confirmed: ba30e28a130f
  - type: mitigates
    target: RSK-4WN2DG
    confirmed: b41c475816a4
---
The encryption layer shall authenticate schedule entries in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly at least once per minute
- No error entries in the device log
