---
id: REQ-A0DXGNP
type: software-requirement
title: Over-temperature monitor authenticates sensor readings
status: Draft
priority: Medium
owner: N. Kamal
former-id: SW-0G88NP
parent: REQ-GCPQ4HC
order: a2
links:
  - type: refines
    target: REQ-GCPQ4HC
    confirmed: 82b2ddf90cf3
---
The watchdog shall limit sensor readings in under 3 s.

**Rationale:** Schedule entries must stay consistent for the user below 0.5 W in standby.
