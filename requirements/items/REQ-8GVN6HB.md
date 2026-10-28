---
id: HW-04D2EA
type: hardware-requirement
title: Main PCB authenticates error conditions
status: Obsolete
priority: Low
owner: É. Laurent
tags:
  - i18n
  - power
  - regulatory
parent: SYS-CEFJX7
order: 20
links:
  - type: refines
    target: SYS-CEFJX7
    confirmed: fadbb8266e08
---
The relay board shall synchronise schedule entries when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly when the network is unavailable
- No error entries in the device log
