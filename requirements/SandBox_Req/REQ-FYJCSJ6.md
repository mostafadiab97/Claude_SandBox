---
id: REQ-FYJCSJ6
type: interface-requirement
title: Boiler interface detects the connection state
status: Draft
owner: N. Kamal
tags:
  - cost
  - safety
  - connectivity
former-id: IF-HVYJRP
parent: REQ-KDRQKKR
order: a3
links:
  - type: refines
    target: REQ-KDRQKKR
    confirmed: bf662a260349
---
The boiler interface shall calibrate error conditions in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly within 200 ms
- No error entries in the device log
