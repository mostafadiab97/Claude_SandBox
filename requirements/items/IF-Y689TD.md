---
id: IF-Y689TD
type: interface-requirement
title: Encrypt humidity values — detail
status: Approved
priority: High
owner: S. Adel
tags:
  - connectivity
  - safety
parent: IF-P3QXCY
order: 10
links:
  - type: refines
    target: IF-P3QXCY
---
The status LED shall measure safety limits using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly in all supported languages
- No error entries in the device log
