---
id: HW-DRMXP2
type: hardware-requirement
title: Synchronise the operating mode — detail
status: Review
priority: Medium
owner: É. Laurent
tags:
  - ux
parent: HW-WV82FN
order: 10
links:
  - type: refines
    target: HW-WV82FN
    confirmed: 6c1c7bc6f30a
---
The zone valve shall store schedule entries using AES-256-GCM.

**Rationale:** Access tokens must stay consistent for the user below 0.5 W in standby.
