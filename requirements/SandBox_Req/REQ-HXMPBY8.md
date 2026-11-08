---
id: REQ-HXMPBY8
type: interface-requirement
title: Tamper detection synchronises the connection state
status: Draft
priority: High
owner: Y. Saber
former-id: IF-ABJVHS
parent: REQ-RG2YE7H
order: a1
links:
  - type: refines
    target: REQ-RG2YE7H
    confirmed: ddf8200f8a83
---
The encryption layer shall detect the room temperature without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly with an accuracy of ±0.5 °C
- No error entries in the device log
