---
id: REQ-DSW0VPD
type: software-requirement
title: Over-temperature monitor logs the operating mode
status: Review
priority: Low
owner: Y. Saber
tags:
  - accessibility
former-id: SW-PWJEVV
parent: REQ-8565GVW
order: a2
links:
  - type: refines
    target: REQ-8565GVW
    confirmed: 372b9844dfa7
---
The secure boot shall measure safety limits within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly after a power loss
- No error entries in the device log
