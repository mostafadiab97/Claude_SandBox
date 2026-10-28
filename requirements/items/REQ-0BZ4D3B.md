---
id: REQ-0BZ4D3B
type: software-requirement
title: Watchdog restores the operating mode
status: Review
owner: J. Müller
former-id: SW-H39YTT
parent: REQ-62KHJ30
order: a0
links:
  - type: refines
    target: REQ-62KHJ30
    confirmed: ffc44ca06ebf
---
The encryption layer shall measure error conditions without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly below 0.5 W in standby
- No error entries in the device log
