---
id: REQ-A76WYDM
type: hardware-requirement
title: Zone valve authenticates relay events
status: Approved
priority: Medium
owner: L. Samir
tags:
  - accessibility
  - i18n
  - security
former-id: HW-20ZCRS
parent: REQ-XTRE6E2
order: a1
links:
  - type: refines
    target: REQ-XTRE6E2
    confirmed: 51ad9fc7ce44
---
The regulation loop shall switch safety limits using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly below 0.5 W in standby
- No error entries in the device log
