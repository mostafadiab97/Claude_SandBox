---
id: REQ-QKQMW5J
type: system-requirement
title: OTA server calibrates the set point
status: Review
priority: Low
owner: A. Hassan
tags:
  - i18n
former-id: SYS-2B7SGQ
parent: REQ-RE9ZKHF
order: aL
links:
  - type: refines
    target: REQ-M17BCB3
    confirmed: ff820400e2f9
---
The OTA server shall report relay events within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly in under 3 s
- No error entries in the device log
