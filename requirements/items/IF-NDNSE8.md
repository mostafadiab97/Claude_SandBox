---
id: IF-NDNSE8
type: interface-requirement
title: Relay board stores the set point
status: Review
priority: Medium
tags:
  - release-1.0
  - performance
  - power
parent: SYS-ESNRC9
order: 10
links:
  - type: refines
    target: SYS-ESNRC9
---
The relay board shall log access tokens when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly for at least 10 years
- No error entries in the device log
