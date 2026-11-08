---
id: REQ-WEPJN4C
type: software-requirement
title: Heating controller validates the room temperature
status: Review
owner: K. Tanaka
tags:
  - connectivity
  - regulatory
  - security
former-id: SW-8T7BET
parent: REQ-42QCGS2
order: a1
links:
  - type: refines
    target: REQ-42QCGS2
    confirmed: 949315efbc71
---
The regulation loop shall calibrate sensor readings after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly without user interaction
- No error entries in the device log
