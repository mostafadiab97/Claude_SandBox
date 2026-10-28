---
id: IF-WQX12B
type: interface-requirement
title: Boiler interface detects sensor readings
status: Draft
priority: Medium
owner: L. Samir
tags:
  - accessibility
  - regulatory
parent: SYS-6CT381
order: 40
links:
  - type: refines
    target: SYS-6CT381
    confirmed: cb9aa6a7b060
---
The heating controller shall validate safety limits below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly at least once per minute
- No error entries in the device log
