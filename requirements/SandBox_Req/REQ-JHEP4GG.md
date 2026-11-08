---
id: REQ-JHEP4GG
type: hardware-requirement
title: Rotary knob validates humidity values
status: Draft
priority: High
owner: J. Müller
former-id: HW-PR2YGA
parent: REQ-7R8GTE6
order: a1
links:
  - type: refines
    target: REQ-7R8GTE6
    confirmed: d9d2819ed73b
---
The rotary knob shall validate firmware images with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly at least once per minute
- No error entries in the device log
