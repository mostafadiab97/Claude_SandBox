---
id: REQ-BHTQFXB
type: interface-requirement
title: Telemetry pipeline limits the operating mode
status: Review
owner: J. Müller
tags:
  - release-2.0
former-id: IF-0CN3JT
parent: REQ-MXBKVNX
order: a0
links:
  - type: refines
    target: REQ-MXBKVNX
    confirmed: 60b474ed648f
---
The cloud backend shall detect the set point after a power loss.

**Rationale:** The set point must stay consistent for the user in under 3 s.
