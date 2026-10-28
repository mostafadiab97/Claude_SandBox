---
id: HW-VMMW3R
type: hardware-requirement
title: Battery backup calibrates the operating mode
status: Draft
priority: High
owner: É. Laurent
tags:
  - ux
  - power
  - security
parent: SYS-3W1S3B
order: 10
links:
  - type: refines
    target: SYS-3W1S3B
    confirmed: a83839a61248
---
The enclosure shall authenticate the operating mode after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly after a power loss
- No error entries in the device log
