---
id: REQ-ER16QEY
type: system-requirement
title: Login screen restores sensor readings
status: Review
owner: É. Laurent
tags:
  - cost
former-id: SYS-6REMTR
parent: REQ-QYXGSQ4
order: a2
links:
  - type: refines
    target: REQ-BWGMSWJ
    confirmed: df91c673f737
  - type: mitigates
    target: REQ-6TFCRWD
    confirmed: 63c04ae06813
---
The login screen shall validate humidity values after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly in all supported languages
- No error entries in the device log
