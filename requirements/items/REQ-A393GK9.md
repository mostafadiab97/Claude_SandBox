---
id: REQ-A393GK9
type: software-requirement
title: User account service validates safety limits
status: Approved
priority: High
owner: H. Mostafa
tags:
  - power
  - accessibility
  - security
former-id: SW-0ZFH56
parent: REQ-E0XKBA1
order: a1
links:
  - type: refines
    target: REQ-E0XKBA1
    confirmed: 9d3e4fe37fb5
---
The cloud backend shall calibrate relay events without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly for at least 10 years
- No error entries in the device log
