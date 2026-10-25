---
id: HW-PVKQ8X
type: hardware-requirement
title: Main PCB validates access tokens
status: Approved
priority: High
tags:
  - power
parent: SYS-1K9BKF
order: 10
links:
  - type: refines
    target: SYS-1K9BKF
    confirmed: c64cd8bb0fb4
---
The battery backup shall measure the connection state at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly with an accuracy of ±0.5 °C
- No error entries in the device log
