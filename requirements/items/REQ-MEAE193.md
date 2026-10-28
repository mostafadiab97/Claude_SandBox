---
id: REQ-MEAE193
type: software-requirement
title: Over-temperature monitor detects the set point
status: Obsolete
priority: Medium
owner: A. Hassan
former-id: SW-56P9P7
parent: REQ-0RW492W
order: a1
links:
  - type: refines
    target: REQ-0RW492W
    confirmed: c3b62ffd68f1
---
The over-temperature monitor shall limit relay events within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly when the network is unavailable
- No error entries in the device log
