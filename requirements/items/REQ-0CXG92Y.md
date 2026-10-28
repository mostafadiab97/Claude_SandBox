---
id: REQ-0CXG92Y
type: hardware-requirement
title: Relay board authenticates energy consumption
status: Approved
priority: Medium
owner: J. Müller
tags:
  - accessibility
former-id: HW-513GC4
parent: REQ-MZJPBNF
order: a0
links:
  - type: refines
    target: REQ-MZJPBNF
    confirmed: 34de3a2ac266
---
The relay board shall synchronise the connection state with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly when the network is unavailable
- No error entries in the device log
