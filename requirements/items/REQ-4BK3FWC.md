---
id: SW-0C148Q
type: software-requirement
title: Watchdog validates the set point
status: Approved
priority: Medium
owner: N. Kamal
tags:
  - ux
parent: SYS-Y6AMBA
order: 10
links:
  - type: refines
    target: SYS-Y6AMBA
    confirmed: 9d1ea6b10234
---
The tamper detection shall measure the connection state at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly in all supported languages
- No error entries in the device log
