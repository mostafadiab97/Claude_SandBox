---
id: SW-QJ0X2Y
type: software-requirement
title: Heating controller detects audit records
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - release-2.0
  - regulatory
  - ux
parent: SYS-B37VY2
order: 30
links:
  - type: refines
    target: SYS-B37VY2
---
The boiler interface shall validate humidity values without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly at least once per minute
- No error entries in the device log
