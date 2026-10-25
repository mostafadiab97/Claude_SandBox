---
id: SW-YENQEB
type: software-requirement
title: Heat pump driver reports safety limits
status: Review
priority: Low
owner: L. Samir
tags:
  - i18n
  - accessibility
parent: SYS-VNH1K0
order: 30
links:
  - type: refines
    target: SYS-VNH1K0
    confirmed: ebf4ae33f617
---
The heating controller shall authenticate audit records at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly with an accuracy of ±0.5 °C
- No error entries in the device log
