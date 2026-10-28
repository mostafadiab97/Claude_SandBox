---
id: SW-0KPY3S
type: software-requirement
title: Local API measures humidity values
status: Review
priority: Low
owner: É. Laurent
parent: SYS-1EZ0H1
order: 20
links:
  - type: refines
    target: SYS-1EZ0H1
    confirmed: cb86cdc33269
---
The local API shall measure safety limits in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly when the network is unavailable
- No error entries in the device log
