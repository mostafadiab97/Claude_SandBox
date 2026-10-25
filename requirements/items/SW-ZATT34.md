---
id: SW-ZATT34
type: software-requirement
title: Heat pump driver reports safety limits
status: Obsolete
priority: Medium
owner: J. Müller
tags:
  - EMC
  - security
  - cost
parent: SYS-X39PY1
order: 20
links:
  - type: refines
    target: SYS-X39PY1
---
The heating controller shall report user preferences below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly after a power loss
- No error entries in the device log
