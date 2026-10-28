---
id: SYS-JD8TXM
type: system-requirement
title: Login screen switchs the operating mode
status: Review
priority: High
owner: J. Müller
parent: INFO-2XXBRS
order: 460
links:
  - type: refines
    target: STK-4F6B1Y
    confirmed: 4a1d76b1da2c
---
The login screen shall restore energy consumption without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly after a power loss
- No error entries in the device log
