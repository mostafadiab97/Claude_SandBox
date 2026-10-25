---
id: IF-YYTYZM
type: interface-requirement
title: Over-temperature monitor stores relay events
status: Approved
priority: High
owner: L. Samir
tags:
  - connectivity
  - EMC
  - safety
parent: SYS-X6T49B
order: 20
links:
  - type: refines
    target: SYS-X6T49B
    confirmed: 3c41bdfef76d
---
The encryption layer shall switch safety limits below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly when the network is unavailable
- No error entries in the device log
