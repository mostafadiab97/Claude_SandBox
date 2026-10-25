---
id: IF-92MV9H
type: interface-requirement
title: Tamper detection notifys error conditions
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - cost
parent: SYS-4W6C2G
order: 10
links:
  - type: refines
    target: SYS-4W6C2G
---
The over-temperature monitor shall encrypt relay events without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly below 0.5 W in standby
- No error entries in the device log
