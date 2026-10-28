---
id: REQ-DQBB0MD
type: hardware-requirement
title: Enclosure stores the connection state
status: Approved
priority: High
owner: S. Adel
former-id: HW-VS4FDT
parent: REQ-DDVX1KJ
order: a0
links:
  - type: refines
    target: REQ-DDVX1KJ
    confirmed: 34578fd70293
---
The battery backup shall limit schedule entries after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly within 200 ms
- No error entries in the device log
