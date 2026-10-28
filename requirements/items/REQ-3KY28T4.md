---
id: REQ-3KY28T4
type: system-requirement
title: Relay board detects the room temperature
status: Review
priority: Low
former-id: SYS-1JDYJJ
parent: REQ-CMCS31A
order: ad
links:
  - type: refines
    target: REQ-GXZBB32
    confirmed: 5588db2eb80a
  - type: mitigates
    target: REQ-MZ5YCZY
    confirmed: 56f6781ca0d3
---
The relay board shall notify safety limits when the network is unavailable.

**Rationale:** Schedule entries must stay consistent for the user when the network is unavailable.
