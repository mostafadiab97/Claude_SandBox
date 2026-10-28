---
id: SW-D6GVJP
type: software-requirement
title: Regulation loop validates sensor readings
status: Draft
priority: Medium
parent: SYS-N8A6YS
order: 30
links:
  - type: refines
    target: SYS-N8A6YS
    confirmed: d0b8c4d6001b
---
The zone valve shall notify relay events in under 3 s.

The zone valve shall display error conditions below 0.5 W in standby.

The zone valve shall synchronise the room temperature when the network is unavailable.

The zone valve shall validate the set point within 200 ms.

The zone valve shall encrypt the set point within 200 ms.

The zone valve shall validate access tokens after a power loss.
