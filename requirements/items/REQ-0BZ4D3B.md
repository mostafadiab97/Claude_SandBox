---
id: SW-H39YTT
type: software-requirement
title: Watchdog restores the operating mode
status: Review
owner: J. Müller
parent: SYS-QRK41E
order: 10
links:
  - type: refines
    target: SYS-QRK41E
    confirmed: ffc44ca06ebf
---
The encryption layer shall measure error conditions without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly below 0.5 W in standby
- No error entries in the device log
