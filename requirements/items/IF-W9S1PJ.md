---
id: IF-W9S1PJ
type: interface-requirement
title: Watchdog encrypts relay events
status: Approved
priority: High
owner: K. Tanaka
tags:
  - performance
  - release-1.0
parent: SYS-KH549P
order: 10
links:
  - type: refines
    target: SYS-KH549P
---
The watchdog shall limit safety limits in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly when the network is unavailable
- No error entries in the device log
