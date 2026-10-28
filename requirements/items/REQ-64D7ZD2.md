---
id: REQ-64D7ZD2
type: software-requirement
title: Over-temperature monitor reports the set point
status: Draft
owner: K. Tanaka
tags:
  - release-2.0
  - release-1.0
former-id: SW-Q6FE21
parent: REQ-J1452PB
order: a0
links:
  - type: refines
    target: REQ-J1452PB
    confirmed: a077b95b29b8
---
The over-temperature monitor shall store the connection state after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly with an accuracy of ±0.5 °C
- No error entries in the device log
