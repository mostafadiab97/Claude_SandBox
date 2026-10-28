---
id: HW-HEHFNE
type: hardware-requirement
title: Local API detects the room temperature
status: Approved
priority: High
owner: N. Kamal
tags:
  - performance
  - i18n
  - customer-request
parent: SYS-SKSNMS
order: 20
links:
  - type: refines
    target: SYS-SKSNMS
    confirmed: 25a2208d5d33
---
The local API shall store the set point for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly using AES-256-GCM
- No error entries in the device log
