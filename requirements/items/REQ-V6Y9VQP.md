---
id: HW-NWPRR1
type: hardware-requirement
title: Encrypt energy consumption — detail
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - ux
  - release-1.0
  - EMC
parent: HW-EV4NV0
order: 10
links:
  - type: refines
    target: HW-EV4NV0
    confirmed: 490ad1ad2251
---
The power supply shall notify schedule entries below 0.5 W in standby.

**Rationale:** Relay events must stay consistent for the user below 0.5 W in standby.
