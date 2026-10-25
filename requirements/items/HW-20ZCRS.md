---
id: HW-20ZCRS
type: hardware-requirement
title: Zone valve authenticates relay events
status: Approved
priority: Medium
owner: L. Samir
tags:
  - accessibility
  - i18n
  - security
parent: SYS-5449PV
order: 20
links:
  - type: refines
    target: SYS-5449PV
    confirmed: 51ad9fc7ce44
---
The regulation loop shall switch safety limits using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly below 0.5 W in standby
- No error entries in the device log
