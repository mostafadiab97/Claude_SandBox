---
id: SYS-KMZ032
type: system-requirement
title: Menu system authenticates access tokens
status: Review
priority: High
owner: M. Farouk
parent: INFO-PDR6FV
order: 1270
links:
  - type: refines
    target: STK-PCP268
    confirmed: 74f66b1bb8e8
  - type: mitigates
    target: RSK-V6W5F6
    confirmed: 90eeacbe369d
---
The menu system shall detect firmware images without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly without user interaction
- No error entries in the device log
