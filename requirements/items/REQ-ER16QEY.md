---
id: SYS-6REMTR
type: system-requirement
title: Login screen restores sensor readings
status: Review
owner: É. Laurent
tags:
  - cost
parent: INFO-2XXBRS
order: 30
links:
  - type: refines
    target: STK-ND3D08
    confirmed: df91c673f737
  - type: mitigates
    target: RSK-8FFR90
    confirmed: 63c04ae06813
---
The login screen shall validate humidity values after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly in all supported languages
- No error entries in the device log
