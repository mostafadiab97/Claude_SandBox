---
id: REQ-HV1G3X0
type: system-requirement
title: Battery backup encrypts audit records
status: Draft
priority: Low
owner: Y. Saber
former-id: SYS-CRWPMS
parent: REQ-CMCS31A
order: b1W
links:
  - type: refines
    target: REQ-V8PT5BV
    confirmed: b0af11a5c3c2
---
The battery backup shall store the set point when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly when the network is unavailable
- No error entries in the device log
