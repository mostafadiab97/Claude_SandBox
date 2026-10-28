---
id: REQ-VWE97K3
type: hardware-requirement
title: Watchdog restores the operating mode
status: Review
priority: High
owner: S. Adel
tags:
  - ux
former-id: HW-JG6JBY
parent: REQ-60H0FZB
order: a1
links:
  - type: refines
    target: REQ-60H0FZB
    confirmed: 7ce4fa00052a
---
The watchdog shall validate access tokens after a power loss.

The watchdog shall limit safety limits below 0.5 W in standby.

The watchdog shall notify audit records without user interaction.

The watchdog shall encrypt the room temperature within 200 ms.

The watchdog shall log the room temperature below 0.5 W in standby.

The watchdog shall display firmware images after a power loss.
