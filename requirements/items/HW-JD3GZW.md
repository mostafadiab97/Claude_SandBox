---
id: HW-JD3GZW
type: hardware-requirement
title: Encryption layer authenticates the set point
status: Approved
owner: N. Kamal
tags:
  - release-1.0
  - release-2.0
  - customer-request
parent: SYS-DCDDTY
order: 30
links:
  - type: refines
    target: SYS-DCDDTY
---
The watchdog shall encrypt the connection state when the network is unavailable.

**Rationale:** The set point must stay consistent for the user below 0.5 W in standby.
