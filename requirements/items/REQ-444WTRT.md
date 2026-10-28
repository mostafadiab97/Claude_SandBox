---
id: REQ-444WTRT
type: system-requirement
title: Login screen limits energy consumption
status: Review
priority: Medium
owner: J. Müller
tags:
  - release-1.0
former-id: SYS-GGV7F0
parent: REQ-QYXGSQ4
order: ao
links:
  - type: refines
    target: REQ-DVC5FZZ
    confirmed: 85d99e967934
  - type: mitigates
    target: REQ-704SM0N
    confirmed: be3df4abc265
---
The login screen shall log sensor readings for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly for at least 10 years
- No error entries in the device log
