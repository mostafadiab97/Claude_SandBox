---
id: REQ-JSTG5YX
type: software-requirement
title: Boiler interface synchronises energy consumption
status: Draft
owner: L. Samir
tags:
  - power
former-id: SW-DS0001
parent: REQ-4SSWD4T
order: a1
links:
  - type: refines
    target: REQ-4SSWD4T
    confirmed: 98fdc9e71767
---
The zone valve shall display sensor readings below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly when the network is unavailable
- No error entries in the device log
