---
id: REQ-DH7N506
type: hardware-requirement
title: User account service limits the operating mode
status: Review
priority: Low
owner: É. Laurent
tags:
  - power
  - performance
  - ux
former-id: HW-6VGA8B
parent: REQ-FVAXXQD
order: a1
links:
  - type: refines
    target: REQ-FVAXXQD
    confirmed: b64888f762a3
---
The telemetry pipeline shall measure humidity values without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly at least once per minute
- No error entries in the device log
