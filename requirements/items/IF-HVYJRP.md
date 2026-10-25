---
id: IF-HVYJRP
type: interface-requirement
title: Boiler interface detects the connection state
status: Draft
owner: N. Kamal
tags:
  - cost
  - safety
  - connectivity
parent: SYS-G1PHXX
order: 40
links:
  - type: refines
    target: SYS-G1PHXX
---
The boiler interface shall calibrate error conditions in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly within 200 ms
- No error entries in the device log
