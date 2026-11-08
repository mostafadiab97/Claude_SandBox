---
id: REQ-60H0FZB
type: system-requirement
title: Watchdog limits energy consumption
status: Approved
priority: Medium
owner: S. Adel
tags:
  - i18n
former-id: SYS-C66JCG
parent: REQ-H9113WA
order: b1e
links:
  - type: refines
    target: REQ-Z2QF8WD
    confirmed: 44235e2789f0
---
The watchdog shall authenticate the room temperature without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly below 0.5 W in standby
- No error entries in the device log
