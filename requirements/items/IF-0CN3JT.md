---
id: IF-0CN3JT
type: interface-requirement
title: Telemetry pipeline limits the operating mode
status: Review
owner: J. Müller
tags:
  - release-2.0
parent: SYS-C084T6
order: 10
links:
  - type: refines
    target: SYS-C084T6
    confirmed: 60b474ed648f
---
The cloud backend shall detect the set point after a power loss.

**Rationale:** The set point must stay consistent for the user in under 3 s.
