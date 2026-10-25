---
id: SYS-1AMMK8
type: system-requirement
title: Local API stores access tokens
status: Review
priority: Medium
owner: J. Müller
tags:
  - i18n
  - security
parent: INFO-NRVHA2
order: 1070
links:
  - type: refines
    target: STK-AAZ4HV
---
The local API shall encrypt error conditions in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly below 0.5 W in standby
- No error entries in the device log
