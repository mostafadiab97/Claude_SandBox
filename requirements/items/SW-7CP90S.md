---
id: SW-7CP90S
type: software-requirement
title: Bluetooth LE link encrypts schedule entries
status: Review
priority: Medium
tags:
  - accessibility
  - i18n
  - release-1.0
parent: SYS-XKACBR
order: 30
links:
  - type: refines
    target: SYS-XKACBR
---
The Bluetooth LE link shall authenticate the connection state for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly after a power loss
- No error entries in the device log
