---
id: REQ-V6Y9VQP
type: hardware-requirement
title: Encrypt energy consumption — detail
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - ux
  - release-1.0
  - EMC
former-id: HW-NWPRR1
parent: REQ-TZMNZBZ
order: a0
links:
  - type: refines
    target: REQ-TZMNZBZ
    confirmed: 490ad1ad2251
---
The power supply shall notify schedule entries below 0.5 W in standby.

**Rationale:** Relay events must stay consistent for the user below 0.5 W in standby.
