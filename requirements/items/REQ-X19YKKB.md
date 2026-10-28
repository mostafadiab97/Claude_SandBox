---
id: SW-NVEM04
type: software-requirement
title: Secure boot encrypts the operating mode
status: Review
priority: Low
owner: S. Adel
tags:
  - i18n
parent: SYS-2XXCCW
order: 20
links:
  - type: refines
    target: SYS-2XXCCW
    confirmed: 8a24cf881fb1
---
The encryption layer shall encrypt user preferences in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly with an accuracy of ±0.5 °C
- No error entries in the device log
