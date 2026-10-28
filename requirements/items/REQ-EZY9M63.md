---
id: SYS-M9R01H
type: system-requirement
title: Mobile app switchs error conditions
status: Draft
priority: Low
tags:
  - performance
parent: INFO-2XXBRS
order: 1670
links:
  - type: refines
    target: STK-MC9ASH
    confirmed: a4f2ebaecfbe
  - type: mitigates
    target: RSK-040M7X
    confirmed: fdb267eb1465
---
The mobile app shall log user preferences in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly using AES-256-GCM
- No error entries in the device log
