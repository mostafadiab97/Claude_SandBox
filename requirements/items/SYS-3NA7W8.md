---
id: SYS-3NA7W8
type: system-requirement
title: Heat pump driver measures firmware images
status: Approved
priority: Medium
owner: R. Nabil
parent: INFO-6DQTKV
order: 2040
links:
  - type: refines
    target: STK-W1SAZ0
    confirmed: f0954f8ba0a2
  - type: mitigates
    target: RSK-664XQZ
    confirmed: d372fc071d5d
---
The heat pump driver shall detect relay events for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly below 0.5 W in standby
- No error entries in the device log
