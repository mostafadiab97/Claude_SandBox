---
id: REQ-8KBPBZ8
type: system-requirement
title: Relay board authenticates error conditions
status: Review
priority: Medium
owner: Y. Saber
former-id: SYS-E79TSB
parent: REQ-CMCS31A
order: b19
links:
  - type: refines
    target: REQ-GXZBB32
    confirmed: 5588db2eb80a
  - type: mitigates
    target: REQ-MZ5YCZY
    confirmed: 56f6781ca0d3
---
The relay board shall notify error conditions below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly below 0.5 W in standby
- No error entries in the device log
