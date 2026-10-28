---
id: REQ-ND2B61F
type: system-requirement
title: Status LED restores the room temperature
status: Draft
tags:
  - ux
  - regulatory
former-id: SYS-PY3FTT
parent: REQ-2ZA2TRZ
order: au
links:
  - type: refines
    target: REQ-XR7FDXB
    confirmed: 07434b0b5615
---
The status LED shall limit safety limits within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly at least once per minute
- No error entries in the device log
