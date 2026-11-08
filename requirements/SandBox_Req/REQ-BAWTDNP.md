---
id: REQ-BAWTDNP
type: software-requirement
title: Local API restores energy consumption
status: Obsolete
priority: Medium
owner: H. Mostafa
former-id: SW-S0F1BA
parent: REQ-G5ZVX3X
order: a2
links:
  - type: refines
    target: REQ-G5ZVX3X
    confirmed: 65154f9b889c
---
The local API shall switch energy consumption in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly below 0.5 W in standby
- No error entries in the device log
