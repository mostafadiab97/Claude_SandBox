---
id: REQ-MDTQB7X
type: hardware-requirement
title: Encryption layer authenticates the set point
status: Approved
owner: N. Kamal
tags:
  - release-1.0
  - release-2.0
  - customer-request
former-id: HW-JD3GZW
parent: REQ-SVAHMDQ
order: a2
links:
  - type: refines
    target: REQ-SVAHMDQ
    confirmed: 5b47c2ab88c1
---
The watchdog shall encrypt the connection state when the network is unavailable.

**Rationale:** The set point must stay consistent for the user below 0.5 W in standby.
