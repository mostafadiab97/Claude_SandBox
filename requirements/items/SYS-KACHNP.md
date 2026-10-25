---
id: SYS-KACHNP
type: system-requirement
title: Cloud backend validates audit records
status: Obsolete
priority: Medium
owner: A. Hassan
parent: INFO-YV5EZD
order: 1000
links:
  - type: refines
    target: STK-8Y3SDF
    confirmed: 2609d2cce998
---
The cloud backend shall authenticate error conditions after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly below 0.5 W in standby
- No error entries in the device log
