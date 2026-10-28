---
id: REQ-NV2EGQT
type: software-requirement
title: Watchdog synchronises error conditions
status: Review
priority: Medium
tags:
  - release-1.0
former-id: SW-6J2ZYG
parent: REQ-85GMKSH
order: a1
links:
  - type: refines
    target: REQ-85GMKSH
    confirmed: 0b455862f511
---
The tamper detection shall validate sensor readings with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly for up to 8 zones
- No error entries in the device log
