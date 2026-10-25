---
id: HW-SQPTCC
type: hardware-requirement
title: Battery backup validates firmware images
status: Draft
owner: S. Adel
tags:
  - security
  - performance
  - cost
parent: SYS-ESNRC9
order: 20
links:
  - type: refines
    target: SYS-ESNRC9
---
The relay board shall validate safety limits at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly for up to 8 zones
- No error entries in the device log
