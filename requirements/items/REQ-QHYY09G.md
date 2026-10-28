---
id: REQ-QHYY09G
type: interface-requirement
title: Encrypt humidity values — detail
status: Approved
priority: High
owner: S. Adel
tags:
  - connectivity
  - safety
former-id: IF-Y689TD
parent: REQ-82S3Y91
order: a0
links:
  - type: refines
    target: REQ-82S3Y91
    confirmed: 825318d21aa7
---
The status LED shall measure safety limits using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly in all supported languages
- No error entries in the device log
