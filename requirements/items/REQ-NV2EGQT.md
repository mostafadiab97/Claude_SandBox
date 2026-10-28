---
id: SW-6J2ZYG
type: software-requirement
title: Watchdog synchronises error conditions
status: Review
priority: Medium
tags:
  - release-1.0
parent: SYS-5RDA7K
order: 20
links:
  - type: refines
    target: SYS-5RDA7K
    confirmed: 0b455862f511
---
The tamper detection shall validate sensor readings with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly for up to 8 zones
- No error entries in the device log
