---
id: SW-XWNQMC
type: software-requirement
title: Boiler interface detects energy consumption
status: Obsolete
priority: High
owner: A. Hassan
parent: SYS-XRXTDN
order: 10
links:
  - type: refines
    target: SYS-XRXTDN
    confirmed: ad932a195f5d
---
The boiler interface shall switch schedule entries when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly at least once per minute
- No error entries in the device log
