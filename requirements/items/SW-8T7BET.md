---
id: SW-8T7BET
type: software-requirement
title: Heating controller validates the room temperature
status: Review
owner: K. Tanaka
tags:
  - connectivity
  - regulatory
  - security
parent: SYS-G3EJDX
order: 20
links:
  - type: refines
    target: SYS-G3EJDX
    confirmed: 949315efbc71
---
The regulation loop shall calibrate sensor readings after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly without user interaction
- No error entries in the device log
