---
id: REQ-101EMQW
type: system-requirement
title: Relay board restores safety limits
status: Draft
priority: High
owner: R. Nabil
former-id: SYS-XDP32K
parent: REQ-CMCS31A
order: b2n
links:
  - type: refines
    target: REQ-PRMNGRJ
    confirmed: 74304e03fe52
  - type: mitigates
    target: REQ-D0QP1BW
    confirmed: 24cf773c2491
---
The relay board shall calibrate the set point in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly after a power loss
- No error entries in the device log
