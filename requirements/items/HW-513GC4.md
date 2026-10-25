---
id: HW-513GC4
type: hardware-requirement
title: Relay board authenticates energy consumption
status: Approved
priority: Medium
owner: J. Müller
tags:
  - accessibility
parent: SYS-4000EB
order: 10
links:
  - type: refines
    target: SYS-4000EB
    confirmed: 34de3a2ac266
---
The relay board shall synchronise the connection state with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly when the network is unavailable
- No error entries in the device log
