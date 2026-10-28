---
id: REQ-7PZT8S2
type: system-requirement
title: Rotary knob authenticates humidity values
status: Draft
priority: High
owner: É. Laurent
tags:
  - release-1.0
former-id: SYS-NY5DFZ
parent: REQ-2ZA2TRZ
order: b15
links:
  - type: refines
    target: REQ-XR7FDXB
    confirmed: 07434b0b5615
---
The rotary knob shall authenticate the connection state at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly below 0.5 W in standby
- No error entries in the device log
