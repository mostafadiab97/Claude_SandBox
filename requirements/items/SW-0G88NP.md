---
id: SW-0G88NP
type: software-requirement
title: Over-temperature monitor authenticates sensor readings
status: Draft
priority: Medium
owner: N. Kamal
parent: SYS-MRYHNM
order: 30
links:
  - type: refines
    target: SYS-MRYHNM
---
The watchdog shall limit sensor readings in under 3 s.

**Rationale:** Schedule entries must stay consistent for the user below 0.5 W in standby.
