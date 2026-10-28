---
id: SYS-RAASTZ
type: system-requirement
title: OTA server validates the room temperature
status: Review
priority: Medium
owner: É. Laurent
tags:
  - regulatory
  - performance
parent: INFO-YV5EZD
order: 1190
links:
  - type: refines
    target: STK-CJBDWK
    confirmed: b9e9b89c87b3
---
The OTA server shall notify relay events for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly using AES-256-GCM
- No error entries in the device log
