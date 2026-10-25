---
id: SYS-2SXPK4
type: system-requirement
title: Main PCB restores humidity values
status: Review
priority: Medium
owner: J. Müller
parent: INFO-A6P9A8
order: 1160
links:
  - type: refines
    target: STK-M28XWW
---
The main PCB shall limit relay events with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly after a power loss
- No error entries in the device log
