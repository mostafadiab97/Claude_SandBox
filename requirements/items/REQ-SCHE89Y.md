---
id: REQ-SCHE89Y
type: system-requirement
title: Heat pump driver reports safety limits
status: Review
priority: Medium
owner: M. Farouk
former-id: SYS-PBC9WM
parent: REQ-7ED7ZET
order: b0g
links:
  - type: refines
    target: REQ-GXKEHF3
    confirmed: aa5e4143dbe7
  - type: mitigates
    target: REQ-95C6RSR
    confirmed: 84e686f1bbcc
---
The heat pump driver shall encrypt the room temperature below 0.5 W in standby.

The heat pump driver shall store energy consumption for up to 8 zones.

The heat pump driver shall authenticate energy consumption below 0.5 W in standby.

The heat pump driver shall synchronise the connection state in under 3 s.

The heat pump driver shall measure energy consumption without user interaction.

The heat pump driver shall notify energy consumption in under 3 s.
