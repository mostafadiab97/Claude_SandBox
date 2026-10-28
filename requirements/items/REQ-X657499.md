---
id: SW-JEHJ48
type: software-requirement
title: Login screen detects energy consumption
status: Review
priority: Medium
parent: SYS-2Y9FGT
order: 10
links:
  - type: refines
    target: SYS-2Y9FGT
    confirmed: 4c561d45744d
---
The login screen shall encrypt access tokens at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly below 0.5 W in standby
- No error entries in the device log
