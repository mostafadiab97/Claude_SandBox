---
id: SW-5WZRHV
type: software-requirement
title: Over-temperature monitor restores error conditions
status: Draft
priority: Medium
owner: N. Kamal
parent: SYS-H80NAW
order: 10
links:
  - type: refines
    target: SYS-H80NAW
    confirmed: d4703e1835f9
---
The encryption layer shall limit error conditions without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly below 0.5 W in standby
- No error entries in the device log
