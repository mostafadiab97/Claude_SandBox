---
id: REQ-B0PGH7P
type: system-requirement
title: Watchdog measures sensor readings
status: Approved
priority: Medium
owner: محمد علي
tags:
  - release-2.0
former-id: SYS-P0EP0R
parent: REQ-H9113WA
order: a6
links:
  - type: refines
    target: REQ-Y7E2CS3
    confirmed: 66c246d6b1dc
---
The watchdog shall restore the operating mode using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly below 0.5 W in standby
- No error entries in the device log
