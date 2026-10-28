---
id: SW-Y2CY20
type: software-requirement
title: Synchronise safety limits — detail
status: Review
priority: High
owner: S. Adel
tags:
  - release-2.0
  - regulatory
parent: SW-BS08SF
order: 10
links:
  - type: refines
    target: SW-BS08SF
    confirmed: 4d5371598d96
---
The over-temperature monitor shall limit access tokens within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly for up to 8 zones
- No error entries in the device log
