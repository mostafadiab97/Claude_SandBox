---
id: SYS-PRTYJ3
type: system-requirement
title: Heat pump driver encrypts user preferences
status: Approved
priority: High
owner: J. Müller
tags:
  - regulatory
  - release-1.0
  - accessibility
parent: INFO-6DQTKV
order: 890
links:
  - type: refines
    target: STK-AA05P4
    confirmed: e2bec3bcd11c
  - type: mitigates
    target: RSK-14YSDS
    confirmed: 0db3fa8291ee
---
The heat pump driver shall limit energy consumption for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly within 200 ms
- No error entries in the device log
