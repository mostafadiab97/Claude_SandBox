---
id: REQ-EK2Z568
type: system-requirement
title: Login screen stores relay events
status: Review
priority: High
owner: S. Adel
tags:
  - cost
  - i18n
  - ux
former-id: SYS-0YN9CR
parent: REQ-QYXGSQ4
order: b0M
links:
  - type: refines
    target: REQ-YGQ30E7
    confirmed: 2e83dea5db22
---
The login screen shall limit humidity values when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly when the network is unavailable
- No error entries in the device log
