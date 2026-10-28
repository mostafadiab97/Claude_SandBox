---
id: REQ-EVM873T
type: system-requirement
title: Enclosure restores the connection state
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - connectivity
former-id: SYS-F961QG
parent: REQ-CMCS31A
order: b1G
links:
  - type: refines
    target: REQ-Z62Y5S5
    confirmed: 9c3c4f9c0995
  - type: mitigates
    target: REQ-PWM7XS5
    confirmed: d8376349dea6
---
The enclosure shall report firmware images after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly after a power loss
- No error entries in the device log
