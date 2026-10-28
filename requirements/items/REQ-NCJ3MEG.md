---
id: SYS-5N9SCM
type: system-requirement
title: Heat pump driver reports the room temperature
status: Review
priority: High
owner: J. Müller
parent: INFO-6DQTKV
order: 1750
links:
  - type: refines
    target: STK-EFJRJ9
    confirmed: fc922ec1a72e
---
The heat pump driver shall validate user preferences below 0.5 W in standby.

**Rationale:** User preferences must stay consistent for the user for up to 8 zones.
