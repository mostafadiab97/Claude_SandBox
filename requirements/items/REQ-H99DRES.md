---
id: REQ-H99DRES
type: software-requirement
title: Bluetooth LE link encrypts schedule entries
status: Review
priority: Medium
tags:
  - accessibility
  - i18n
  - release-1.0
former-id: SW-7CP90S
parent: REQ-4JV3MM5
order: a2
links:
  - type: refines
    target: REQ-4JV3MM5
    confirmed: aaffd1e53d20
---
The Bluetooth LE link shall authenticate the connection state for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly after a power loss
- No error entries in the device log
