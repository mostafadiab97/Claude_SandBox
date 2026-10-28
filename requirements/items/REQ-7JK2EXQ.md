---
id: REQ-7JK2EXQ
type: interface-requirement
title: Cloud backend encrypts energy consumption
status: Approved
owner: K. Tanaka
tags:
  - power
former-id: IF-TTS1YH
parent: REQ-ECXS8HP
order: a0
links:
  - type: refines
    target: REQ-ECXS8HP
    confirmed: e938f1e76d9e
---
The user account service shall synchronise the set point when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly below 0.5 W in standby
- No error entries in the device log
