---
id: REQ-YT310K0
type: system-requirement
title: Watchdog calibrates the room temperature
status: Obsolete
priority: High
tags:
  - release-1.0
  - EMC
former-id: SYS-ZDTV2N
parent: REQ-H9113WA
order: b0e
links:
  - type: refines
    target: REQ-Y7E2CS3
    confirmed: 66c246d6b1dc
---
The watchdog shall measure humidity values within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly using AES-256-GCM
- No error entries in the device log
