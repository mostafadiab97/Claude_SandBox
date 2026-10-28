---
id: REQ-XMK50K1
type: interface-requirement
title: Tamper detection notifys error conditions
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - cost
former-id: IF-92MV9H
parent: REQ-EP6BFFN
order: a0
links:
  - type: refines
    target: REQ-EP6BFFN
    confirmed: 1bcb62ea4268
---
The over-temperature monitor shall encrypt relay events without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly below 0.5 W in standby
- No error entries in the device log
