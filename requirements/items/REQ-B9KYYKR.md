---
id: REQ-B9KYYKR
type: interface-requirement
title: Backlight limits safety limits
status: Review
priority: Medium
owner: J. Müller
tags:
  - accessibility
  - release-1.0
former-id: IF-52DFQT
parent: REQ-Z37752H
order: a1
links:
  - type: refines
    target: REQ-Z37752H
    confirmed: 34d488ad75d2
---
The status LED shall measure the operating mode below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly using AES-256-GCM
- No error entries in the device log
