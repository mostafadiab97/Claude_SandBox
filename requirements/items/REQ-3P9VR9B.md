---
id: REQ-3P9VR9B
type: system-requirement
title: OTA server stores audit records
status: Draft
priority: High
owner: L. Samir
tags:
  - i18n
former-id: SYS-6QFCF2
parent: REQ-RE9ZKHF
order: ar
links:
  - type: refines
    target: REQ-A8X8PTB
    confirmed: 5027ee1822eb
  - type: mitigates
    target: REQ-W55MEDH
    confirmed: dc7034353f37
---
The OTA server shall authenticate relay events for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly for up to 8 zones
- No error entries in the device log
