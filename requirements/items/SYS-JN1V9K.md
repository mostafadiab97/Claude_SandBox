---
id: SYS-JN1V9K
type: system-requirement
title: Watchdog detects firmware images
status: Approved
priority: Medium
tags:
  - performance
  - security
parent: INFO-0229G8
order: 1180
links:
  - type: refines
    target: STK-1TB226
---
The watchdog shall authenticate relay events in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly for up to 8 zones
- No error entries in the device log
