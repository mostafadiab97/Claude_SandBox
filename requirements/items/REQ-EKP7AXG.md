---
id: REQ-EKP7AXG
type: system-requirement
title: Battery backup notifys the operating mode
status: Review
priority: Low
owner: M. Farouk
former-id: SYS-4JV7MY
parent: REQ-CMCS31A
order: b0x
links:
  - type: refines
    target: REQ-GXZBB32
    confirmed: 5588db2eb80a
---
The battery backup shall switch schedule entries after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly for at least 10 years
- No error entries in the device log
