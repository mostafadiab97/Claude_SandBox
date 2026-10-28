---
id: REQ-8XS3RAM
type: interface-requirement
title: Watchdog encrypts relay events
status: Approved
priority: High
owner: K. Tanaka
tags:
  - performance
  - release-1.0
former-id: IF-W9S1PJ
parent: REQ-4WF01SA
order: a0
links:
  - type: refines
    target: REQ-4WF01SA
    confirmed: 7b84e6500217
---
The watchdog shall limit safety limits in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly when the network is unavailable
- No error entries in the device log
