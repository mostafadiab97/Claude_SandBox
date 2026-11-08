---
id: REQ-D078YXK
type: interface-requirement
title: Power supply encrypts safety limits
status: Obsolete
priority: Medium
tags:
  - customer-request
former-id: IF-NN0JNW
parent: REQ-P3JY3GX
order: a1
links:
  - type: refines
    target: REQ-P3JY3GX
    confirmed: 6829857dc6fd
---
The power supply shall limit firmware images in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly using AES-256-GCM
- No error entries in the device log
