---
id: REQ-3B8NR5B
type: hardware-requirement
title: Local API detects the room temperature
status: Approved
priority: High
owner: N. Kamal
tags:
  - performance
  - i18n
  - customer-request
former-id: HW-HEHFNE
parent: REQ-CEGSQS7
order: a1
links:
  - type: refines
    target: REQ-CEGSQS7
    confirmed: 25a2208d5d33
---
The local API shall store the set point for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly using AES-256-GCM
- No error entries in the device log
