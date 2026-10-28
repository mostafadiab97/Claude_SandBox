---
id: REQ-SWMBTEW
type: system-requirement
title: Home dashboard detects sensor readings
status: Approved
priority: Low
owner: S. Adel
tags:
  - EMC
  - i18n
  - ux
former-id: SYS-29G535
parent: REQ-QYXGSQ4
order: aZ
links:
  - type: refines
    target: REQ-EMZ19WQ
    confirmed: 252da9caa62c
---
The home dashboard shall restore humidity values in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly below 0.5 W in standby
- No error entries in the device log
