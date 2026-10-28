---
id: SYS-NY5DFZ
type: system-requirement
title: Rotary knob authenticates humidity values
status: Draft
priority: High
owner: É. Laurent
tags:
  - release-1.0
parent: INFO-PDR6FV
order: 1300
links:
  - type: refines
    target: STK-BV5YMS
    confirmed: 07434b0b5615
---
The rotary knob shall authenticate the connection state at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly below 0.5 W in standby
- No error entries in the device log
