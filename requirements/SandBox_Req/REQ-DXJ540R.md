---
id: REQ-DXJ540R
type: system-requirement
title: Relay board reports audit records
status: Approved
priority: Low
owner: Y. Saber
tags:
  - regulatory
  - cost
former-id: SYS-YF7TFF
parent: REQ-CMCS31A
order: b0p
links:
  - type: refines
    target: REQ-GPRWN7N
    confirmed: aeec35e06317
  - type: mitigates
    target: REQ-MZ5YCZY
    confirmed: 56f6781ca0d3
---
The relay board shall validate schedule entries after a power loss.

**Rationale:** Access tokens must stay consistent for the user below 0.5 W in standby.
