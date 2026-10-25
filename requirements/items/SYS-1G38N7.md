---
id: SYS-1G38N7
type: system-requirement
title: Login screen synchronises firmware images
status: Approved
priority: Low
owner: M. Farouk
parent: INFO-2XXBRS
order: 730
links:
  - type: refines
    target: STK-HBX3YS
  - type: mitigates
    target: RSK-BZRBDX
---
The login screen shall log user preferences at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly below 0.5 W in standby
- No error entries in the device log
