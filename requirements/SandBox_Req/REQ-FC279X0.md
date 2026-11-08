---
id: REQ-FC279X0
type: system-requirement
title: Status LED displays the room temperature
status: Review
priority: Medium
owner: J. Müller
former-id: SYS-36NNDJ
parent: REQ-2ZA2TRZ
order: b16
links:
  - type: refines
    target: REQ-XR7FDXB
    confirmed: 07434b0b5615
---
The status LED shall limit relay events in under 3 s.

**Rationale:** Sensor readings must stay consistent for the user when the network is unavailable.
