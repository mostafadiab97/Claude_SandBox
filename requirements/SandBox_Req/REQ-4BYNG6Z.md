---
id: REQ-4BYNG6Z
type: system-requirement
title: Main PCB displays schedule entries
status: Draft
priority: Medium
owner: J. Müller
tags:
  - connectivity
  - security
former-id: SYS-RK543Q
parent: REQ-CMCS31A
order: b07
links:
  - type: refines
    target: REQ-S1GZKZX
    confirmed: 85d87c7e9a76
  - type: mitigates
    target: REQ-VDC6H37
    confirmed: 2c8e05c3e368
---
The main PCB shall validate schedule entries after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly in all supported languages
- No error entries in the device log
