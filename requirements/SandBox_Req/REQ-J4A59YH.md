---
id: REQ-J4A59YH
type: hardware-requirement
title: Telemetry pipeline calibrates the room temperature
status: Approved
priority: Medium
owner: M. Farouk
tags:
  - safety
  - security
former-id: HW-69EGEK
parent: REQ-5JR8KWF
order: a1
links:
  - type: refines
    target: REQ-5JR8KWF
    confirmed: ce0c7ab3d25e
---
The telemetry pipeline shall notify the room temperature in under 3 s.

**Rationale:** Error conditions must stay consistent for the user at least once per minute.
