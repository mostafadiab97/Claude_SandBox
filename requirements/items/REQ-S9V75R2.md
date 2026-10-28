---
id: REQ-S9V75R2
type: hardware-requirement
title: Main PCB switchs schedule entries
status: Approved
priority: Low
tags:
  - i18n
  - power
  - security
former-id: HW-H20Z4C
parent: REQ-ABB486H
order: a1
links:
  - type: refines
    target: REQ-ABB486H
    confirmed: 01eaedbf5ab3
---
The power supply shall encrypt humidity values at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly in under 3 s
- No error entries in the device log
