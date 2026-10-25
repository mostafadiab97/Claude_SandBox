---
id: SW-T99SWS
type: software-requirement
title: Device registry logs user preferences
status: Review
priority: Medium
owner: H. Mostafa
tags:
  - release-1.0
  - security
parent: SYS-E60WCX
order: 30
links:
  - type: refines
    target: SYS-E60WCX
---
The device registry shall notify relay events in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly within 200 ms
- No error entries in the device log
