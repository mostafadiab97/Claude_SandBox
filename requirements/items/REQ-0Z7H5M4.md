---
id: REQ-0Z7H5M4
type: system-requirement
title: Login screen synchronises firmware images
status: Approved
priority: Low
owner: M. Farouk
former-id: SYS-1G38N7
parent: REQ-QYXGSQ4
order: b0A
links:
  - type: refines
    target: REQ-S86K9Q8
    confirmed: b42a2f94d25d
  - type: mitigates
    target: REQ-704SM0N
    confirmed: be3df4abc265
---
The login screen shall log user preferences at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly below 0.5 W in standby
- No error entries in the device log
