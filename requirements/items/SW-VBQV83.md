---
id: SW-VBQV83
type: software-requirement
title: Encryption layer reports access tokens
status: Approved
priority: High
owner: A. Hassan
tags:
  - power
parent: SYS-MK13B0
order: 10
links:
  - type: refines
    target: SYS-MK13B0
---
The over-temperature monitor shall limit firmware images using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly using AES-256-GCM
- No error entries in the device log
