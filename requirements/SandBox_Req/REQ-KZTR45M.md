---
id: REQ-KZTR45M
type: system-requirement
title: Login screen validates sensor readings
status: Draft
priority: Medium
owner: محمد علي
tags:
  - ux
  - regulatory
  - connectivity
former-id: SYS-EMNHY1
parent: REQ-QYXGSQ4
order: b2D
links:
  - type: refines
    target: REQ-BWGMSWJ
    confirmed: df91c673f737
  - type: mitigates
    target: REQ-1CKR5QB
    confirmed: ce36fe2999cf
---
The login screen shall measure the room temperature for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly for at least 10 years
- No error entries in the device log
