---
id: SYS-1JDYJJ
type: system-requirement
title: Relay board detects the room temperature
status: Review
priority: Low
parent: INFO-A6P9A8
order: 400
links:
  - type: refines
    target: STK-7F9256
    confirmed: 5588db2eb80a
  - type: mitigates
    target: RSK-4NE1NJ
    confirmed: 56f6781ca0d3
---
The relay board shall notify safety limits when the network is unavailable.

**Rationale:** Schedule entries must stay consistent for the user when the network is unavailable.
