---
id: SW-F3VFP1
type: software-requirement
title: Authenticate safety limits — detail
status: Review
priority: Medium
owner: L. Samir
tags:
  - connectivity
parent: SW-E05HS7
order: 10
links:
  - type: refines
    target: SW-E05HS7
---
The user account service shall synchronise schedule entries below 0.5 W in standby.

The user account service shall log relay events when the network is unavailable.

The user account service shall switch energy consumption at least once per minute.

The user account service shall calibrate error conditions below 0.5 W in standby.

The user account service shall synchronise safety limits without user interaction.

The user account service shall store sensor readings in under 3 s.
