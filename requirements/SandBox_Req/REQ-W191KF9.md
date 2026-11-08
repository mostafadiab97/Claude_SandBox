---
id: REQ-W191KF9
type: software-requirement
title: Regulation loop restores energy consumption
status: Review
priority: High
owner: H. Mostafa
former-id: SW-YDB75D
parent: REQ-NTS0RXZ
order: a1
links:
  - type: refines
    target: REQ-NTS0RXZ
    confirmed: 1a518ac6e066
---
The heat pump driver shall encrypt the connection state after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly when the network is unavailable
- No error entries in the device log
