---
id: SYS-RK543Q
type: system-requirement
title: Main PCB displays schedule entries
status: Draft
priority: Medium
owner: J. Müller
tags:
  - connectivity
  - security
parent: INFO-A6P9A8
order: 700
links:
  - type: refines
    target: STK-TT8FXG
    confirmed: 85d87c7e9a76
  - type: mitigates
    target: RSK-CYTG6T
    confirmed: 2c8e05c3e368
---
The main PCB shall validate schedule entries after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly in all supported languages
- No error entries in the device log
