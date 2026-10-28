---
id: IF-NN0JNW
type: interface-requirement
title: Power supply encrypts safety limits
status: Obsolete
priority: Medium
tags:
  - customer-request
parent: SYS-AYSZZY
order: 20
links:
  - type: refines
    target: SYS-AYSZZY
    confirmed: 6829857dc6fd
---
The power supply shall limit firmware images in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly using AES-256-GCM
- No error entries in the device log
