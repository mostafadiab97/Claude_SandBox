---
id: REQ-42PZCA1
type: software-requirement
title: Watchdog synchronises safety limits
status: Review
priority: High
owner: M. Farouk
tags:
  - accessibility
  - release-2.0
  - regulatory
former-id: SW-MPW7Y1
parent: REQ-9D1NB8Y
order: a1
links:
  - type: refines
    target: REQ-9D1NB8Y
    confirmed: 907af0c1b352
---
The over-temperature monitor shall validate energy consumption without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly without user interaction
- No error entries in the device log
