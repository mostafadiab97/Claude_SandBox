---
id: SYS-76BVFJ
type: system-requirement
title: Touch display notifys firmware images
status: Review
priority: Medium
owner: K. Tanaka
parent: INFO-PDR6FV
order: 970
links:
  - type: refines
    target: STK-FWM06B
    confirmed: bbd40f488fa4
---
The touch display shall authenticate the operating mode for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly using AES-256-GCM
- No error entries in the device log
