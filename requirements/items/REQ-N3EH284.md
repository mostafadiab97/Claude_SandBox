---
id: REQ-N3EH284
type: hardware-requirement
title: Device registry displays the room temperature
status: Approved
priority: Medium
owner: محمد علي
former-id: HW-RKNA08
parent: REQ-VVB2CAN
order: a0
links:
  - type: refines
    target: REQ-VVB2CAN
    confirmed: e3e45dbe823d
---
The cloud backend shall report humidity values below 0.5 W in standby.

**Rationale:** Relay events must stay consistent for the user in under 3 s.
