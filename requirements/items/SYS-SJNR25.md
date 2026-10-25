---
id: SYS-SJNR25
type: system-requirement
title: Main PCB calibrates access tokens
status: Draft
priority: Low
owner: M. Farouk
tags:
  - security
parent: INFO-A6P9A8
order: 1660
links:
  - type: refines
    target: STK-4NGQJ5
---
The main PCB shall store relay events after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly using AES-256-GCM
- No error entries in the device log
