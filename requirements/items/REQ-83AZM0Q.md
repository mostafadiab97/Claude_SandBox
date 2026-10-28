---
id: REQ-83AZM0Q
type: interface-requirement
title: Pairing process validates energy consumption
status: Review
priority: Medium
owner: J. Müller
former-id: IF-WHB1NV
parent: REQ-Q1BR7H4
order: a3
links:
  - type: refines
    target: REQ-Q1BR7H4
    confirmed: e4a2c3843dd6
---
The Bluetooth LE link shall display schedule entries below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly for up to 8 zones
- No error entries in the device log
