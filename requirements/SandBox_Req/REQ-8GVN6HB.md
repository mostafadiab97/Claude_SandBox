---
id: REQ-8GVN6HB
type: hardware-requirement
title: Main PCB authenticates error conditions
status: Obsolete
priority: Low
owner: É. Laurent
tags:
  - i18n
  - power
  - regulatory
former-id: HW-04D2EA
parent: REQ-6W1TW82
order: a1
links:
  - type: refines
    target: REQ-6W1TW82
    confirmed: fadbb8266e08
---
The relay board shall synchronise schedule entries when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly when the network is unavailable
- No error entries in the device log
