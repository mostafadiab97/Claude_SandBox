---
id: REQ-B5QMB9G
type: interface-requirement
title: Bluetooth LE link stores firmware images
status: Obsolete
priority: Medium
owner: R. Nabil
tags:
  - power
  - accessibility
  - safety
former-id: IF-7CHX48
parent: REQ-Q1BR7H4
order: a2
links:
  - type: refines
    target: REQ-Q1BR7H4
    confirmed: e4a2c3843dd6
---
The Bluetooth LE link shall report firmware images at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly after a power loss
- No error entries in the device log
