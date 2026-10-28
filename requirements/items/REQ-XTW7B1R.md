---
id: SYS-S5AVVB
type: system-requirement
title: User account service detects relay events
status: Review
priority: Medium
parent: INFO-YV5EZD
order: 40
links:
  - type: refines
    target: STK-8Y3SDF
    confirmed: 2609d2cce998
---
The user account service shall report relay events when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly at least once per minute
- No error entries in the device log
