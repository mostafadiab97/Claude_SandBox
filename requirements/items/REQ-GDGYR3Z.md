---
id: REQ-GDGYR3Z
type: software-requirement
title: Heat pump driver reports safety limits
status: Review
priority: Low
owner: L. Samir
tags:
  - i18n
  - accessibility
former-id: SW-YENQEB
parent: REQ-58E6B2T
order: a2
links:
  - type: refines
    target: REQ-58E6B2T
    confirmed: ebf4ae33f617
---
The heating controller shall authenticate audit records at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly with an accuracy of ±0.5 °C
- No error entries in the device log
