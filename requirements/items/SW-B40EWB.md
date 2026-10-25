---
id: SW-B40EWB
type: software-requirement
title: Watchdog authenticates sensor readings
status: Approved
owner: S. Adel
parent: SYS-FP2QK1
order: 10
links:
  - type: refines
    target: SYS-FP2QK1
---
The secure boot shall restore relay events without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly after a power loss
- No error entries in the device log
