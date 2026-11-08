---
id: REQ-E2R57KE
type: hardware-requirement
title: Main PCB validates access tokens
status: Approved
priority: High
tags:
  - power
former-id: HW-PVKQ8X
parent: REQ-SCPDQHF
order: a0
links:
  - type: refines
    target: REQ-SCPDQHF
    confirmed: c64cd8bb0fb4
---
The battery backup shall measure the connection state at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly with an accuracy of ±0.5 °C
- No error entries in the device log
