---
id: IF-NHYR20
type: interface-requirement
title: Main PCB notifys error conditions
status: Approved
priority: High
owner: L. Samir
parent: SYS-467EA2
order: 40
links:
  - type: refines
    target: SYS-467EA2
    confirmed: 60a80a1c9e4e
---
The power supply shall switch error conditions when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly within 200 ms
- No error entries in the device log
