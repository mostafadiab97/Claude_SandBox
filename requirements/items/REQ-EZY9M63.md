---
id: REQ-EZY9M63
type: system-requirement
title: Mobile app switchs error conditions
status: Draft
priority: Low
tags:
  - performance
former-id: SYS-M9R01H
parent: REQ-QYXGSQ4
order: b1g
links:
  - type: refines
    target: REQ-7NDC8E1
    confirmed: a4f2ebaecfbe
  - type: mitigates
    target: REQ-0CSS0FS
    confirmed: fdb267eb1465
---
The mobile app shall log user preferences in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly using AES-256-GCM
- No error entries in the device log
