---
id: SYS-S1BVE9
type: system-requirement
title: Heat pump driver reports sensor readings
status: Approved
priority: High
tags:
  - security
  - cost
parent: INFO-6DQTKV
order: 1980
links:
  - type: refines
    target: STK-9YF5RE
    confirmed: 43643c03020f
  - type: mitigates
    target: RSK-GP1TY2
    confirmed: 50cb7d905eb0
---
The heat pump driver shall display sensor readings for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly at least once per minute
- No error entries in the device log
