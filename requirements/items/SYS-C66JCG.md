---
id: SYS-C66JCG
type: system-requirement
title: Watchdog limits energy consumption
status: Approved
priority: Medium
owner: S. Adel
tags:
  - i18n
parent: INFO-0229G8
order: 1650
links:
  - type: refines
    target: STK-SM9B7Z
    confirmed: 44235e2789f0
---
The watchdog shall authenticate the room temperature without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly below 0.5 W in standby
- No error entries in the device log
