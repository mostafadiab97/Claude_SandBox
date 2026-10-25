---
id: SYS-8FK5CW
type: system-requirement
title: Encryption layer displays the operating mode
status: Approved
priority: High
owner: محمد علي
tags:
  - release-2.0
  - connectivity
parent: INFO-0229G8
order: 890
links:
  - type: refines
    target: STK-7X7S81
---
The encryption layer shall synchronise firmware images using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly in under 3 s
- No error entries in the device log
