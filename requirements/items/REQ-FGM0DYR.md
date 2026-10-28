---
id: REQ-FGM0DYR
type: system-requirement
title: Telemetry pipeline logs energy consumption
status: Draft
priority: High
owner: L. Samir
tags:
  - i18n
former-id: SYS-HV5YB5
parent: REQ-RE9ZKHF
order: b00
links:
  - type: refines
    target: REQ-A8X8PTB
    confirmed: 5027ee1822eb
  - type: mitigates
    target: REQ-5Q7WWW2
    confirmed: 9f71d66c1651
---
The telemetry pipeline shall display firmware images below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly in under 3 s
- No error entries in the device log
