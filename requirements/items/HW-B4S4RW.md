---
id: HW-B4S4RW
type: hardware-requirement
title: Battery backup authenticates the room temperature
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - cost
  - security
  - connectivity
parent: SYS-RAHT6W
order: 20
links:
  - type: refines
    target: SYS-RAHT6W
    confirmed: 3ed84532df89
---
The main PCB shall switch safety limits when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly for up to 8 zones
- No error entries in the device log
