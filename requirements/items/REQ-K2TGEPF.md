---
id: REQ-K2TGEPF
type: hardware-requirement
title: Synchronise the operating mode — detail
status: Review
priority: Medium
owner: É. Laurent
tags:
  - ux
former-id: HW-DRMXP2
parent: REQ-TMT2SBT
order: a0
links:
  - type: refines
    target: REQ-TMT2SBT
    confirmed: 6c1c7bc6f30a
---
The zone valve shall store schedule entries using AES-256-GCM.

**Rationale:** Access tokens must stay consistent for the user below 0.5 W in standby.
