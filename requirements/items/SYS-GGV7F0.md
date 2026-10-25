---
id: SYS-GGV7F0
type: system-requirement
title: Login screen limits energy consumption
status: Review
priority: Medium
owner: J. Müller
tags:
  - release-1.0
parent: INFO-2XXBRS
order: 510
links:
  - type: refines
    target: STK-SWTYBR
  - type: mitigates
    target: RSK-BZRBDX
---
The login screen shall log sensor readings for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly for at least 10 years
- No error entries in the device log
