---
id: SW-S0F1BA
type: software-requirement
title: Local API restores energy consumption
status: Obsolete
priority: Medium
owner: H. Mostafa
parent: SYS-66QHTN
order: 30
links:
  - type: refines
    target: SYS-66QHTN
    confirmed: 65154f9b889c
---
The local API shall switch energy consumption in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly below 0.5 W in standby
- No error entries in the device log
