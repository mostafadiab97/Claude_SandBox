---
id: REQ-KFZ8SY2
type: software-requirement
title: Local API restores humidity values
status: Review
priority: High
owner: A. Hassan
tags:
  - customer-request
  - ux
  - EMC
former-id: SW-0S985C
parent: REQ-TK985W8
order: a1
links:
  - type: refines
    target: REQ-TK985W8
    confirmed: 6b7fab82fc75
---
The local API shall authenticate sensor readings in under 3 s.

**Rationale:** Humidity values must stay consistent for the user with an accuracy of ±0.5 °C.
