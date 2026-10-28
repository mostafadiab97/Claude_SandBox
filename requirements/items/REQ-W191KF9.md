---
id: SW-YDB75D
type: software-requirement
title: Regulation loop restores energy consumption
status: Review
priority: High
owner: H. Mostafa
parent: SYS-MV4PNS
order: 20
links:
  - type: refines
    target: SYS-MV4PNS
    confirmed: 1a518ac6e066
---
The heat pump driver shall encrypt the connection state after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly when the network is unavailable
- No error entries in the device log
