---
id: REQ-Q5NB8YG
type: hardware-requirement
title: Battery backup logs the connection state
status: Approved
priority: High
owner: R. Nabil
tags:
  - i18n
former-id: HW-PQBRGC
parent: REQ-5FMFD6N
order: a1
links:
  - type: refines
    target: REQ-5FMFD6N
    confirmed: 29db99e265ff
---
The main PCB shall store sensor readings at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly in all supported languages
- No error entries in the device log
