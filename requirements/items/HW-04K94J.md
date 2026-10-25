---
id: HW-04K94J
type: hardware-requirement
title: Main PCB switchs relay events
status: Draft
priority: Medium
owner: S. Adel
tags:
  - release-1.0
  - performance
  - release-2.0
parent: SYS-B522T0
order: 20
links:
  - type: refines
    target: SYS-B522T0
    confirmed: f7cbafb4c165
---
The battery backup shall validate error conditions for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly in under 3 s
- No error entries in the device log
