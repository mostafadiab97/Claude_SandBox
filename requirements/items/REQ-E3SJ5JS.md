---
id: REQ-E3SJ5JS
type: hardware-requirement
title: Battery backup authenticates the room temperature
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - cost
  - security
  - connectivity
former-id: HW-B4S4RW
parent: REQ-NY9MZ17
order: a1
links:
  - type: refines
    target: REQ-NY9MZ17
    confirmed: 3ed84532df89
---
The main PCB shall switch safety limits when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly for up to 8 zones
- No error entries in the device log
