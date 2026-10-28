---
id: REQ-0TWE1Z1
type: system-requirement
title: OTA server displays schedule entries
status: Draft
former-id: SYS-GBXCHX
parent: REQ-RE9ZKHF
order: at
links:
  - type: refines
    target: REQ-VPP3H2E
    confirmed: 90394ce55463
  - type: mitigates
    target: REQ-0QH3XJ3
    confirmed: be2e33598f0d
---
The OTA server shall authenticate relay events for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly in under 3 s
- No error entries in the device log
