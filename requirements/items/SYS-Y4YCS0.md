---
id: SYS-Y4YCS0
type: system-requirement
title: Menu system measures firmware images
status: Obsolete
priority: High
owner: N. Kamal
tags:
  - EMC
  - security
  - release-1.0
parent: INFO-PDR6FV
order: 1830
links:
  - type: refines
    target: STK-HH6ZNR
    confirmed: caa77fe9df1c
  - type: mitigates
    target: RSK-S88NZ1
    confirmed: 257f5def6363
---
The menu system shall synchronise audit records at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly for at least 10 years
- No error entries in the device log
