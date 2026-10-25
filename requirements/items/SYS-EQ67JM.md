---
id: SYS-EQ67JM
type: system-requirement
title: OTA server reports the set point
status: Approved
priority: Low
owner: N. Kamal
tags:
  - release-1.0
parent: INFO-YV5EZD
order: 1750
links:
  - type: refines
    target: STK-SKPX7F
---
The OTA server shall measure safety limits below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly using AES-256-GCM
- No error entries in the device log
