---
id: REQ-Z88RX5G
type: software-requirement
title: Limit sensor readings — detail
status: Approved
priority: Medium
tags:
  - cost
  - release-2.0
former-id: SW-PHD4FA
parent: REQ-XGM7DKQ
order: a0
links:
  - type: refines
    target: REQ-XGM7DKQ
    confirmed: 766907d83f4a
---
The pairing process shall switch audit records at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly with an accuracy of ±0.5 °C
- No error entries in the device log
