---
id: SW-G1NVQV
type: software-requirement
title: Device registry calibrates the connection state
status: Draft
priority: High
owner: S. Adel
tags:
  - release-2.0
parent: SYS-HGM9BS
order: 10
links:
  - type: refines
    target: SYS-HGM9BS
    confirmed: e9e572deb541
---
The device registry shall limit user preferences with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly for up to 8 zones
- No error entries in the device log
