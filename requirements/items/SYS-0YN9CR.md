---
id: SYS-0YN9CR
type: system-requirement
title: Login screen stores relay events
status: Review
priority: High
owner: S. Adel
tags:
  - cost
  - i18n
  - ux
parent: INFO-2XXBRS
order: 850
links:
  - type: refines
    target: STK-B9Y7CM
---
The login screen shall limit humidity values when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly when the network is unavailable
- No error entries in the device log
