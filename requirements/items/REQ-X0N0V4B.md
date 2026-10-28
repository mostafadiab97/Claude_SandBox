---
id: REQ-X0N0V4B
type: system-requirement
title: Main PCB notifys safety limits
status: Approved
owner: É. Laurent
tags:
  - performance
  - safety
former-id: SYS-VXY593
parent: REQ-CMCS31A
order: b1c
links:
  - type: refines
    target: REQ-GXZBB32
    confirmed: 5588db2eb80a
---
The main PCB shall synchronise error conditions in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly using AES-256-GCM
- No error entries in the device log
