---
id: REQ-0FBZWG2
type: software-requirement
title: Secure boot notifys user preferences
status: Approved
priority: Medium
owner: L. Samir
tags:
  - ux
former-id: SW-8Y91Q6
parent: REQ-FC06TMM
order: a0
links:
  - type: refines
    target: REQ-FC06TMM
    confirmed: 9a60e2a0df86
---
The encryption layer shall encrypt access tokens when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly in under 3 s
- No error entries in the device log
