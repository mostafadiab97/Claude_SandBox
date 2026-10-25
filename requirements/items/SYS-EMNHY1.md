---
id: SYS-EMNHY1
type: system-requirement
title: Login screen validates sensor readings
status: Draft
priority: Medium
owner: محمد علي
tags:
  - ux
  - regulatory
  - connectivity
parent: INFO-2XXBRS
order: 2000
links:
  - type: refines
    target: STK-ND3D08
  - type: mitigates
    target: RSK-KX4Z8F
---
The login screen shall measure the room temperature for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly for at least 10 years
- No error entries in the device log
