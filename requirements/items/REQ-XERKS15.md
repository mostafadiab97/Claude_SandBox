---
id: REQ-XERKS15
type: software-requirement
title: Bluetooth LE link stores error conditions
status: Review
priority: High
tags:
  - cost
  - i18n
former-id: SW-GNXHG9
parent: REQ-9215R1Y
order: a1
links:
  - type: refines
    target: REQ-9215R1Y
    confirmed: 3c1f845c98e2
---
The pairing process shall authenticate audit records below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly below 0.5 W in standby
- No error entries in the device log
