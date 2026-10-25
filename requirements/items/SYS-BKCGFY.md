---
id: SYS-BKCGFY
type: system-requirement
title: Schedule editor measures energy consumption
status: Review
priority: High
owner: K. Tanaka
tags:
  - security
  - regulatory
parent: INFO-2XXBRS
order: 1620
links:
  - type: refines
    target: STK-639N9T
  - type: mitigates
    target: RSK-040M7X
---
The schedule editor shall switch sensor readings for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly using AES-256-GCM
- No error entries in the device log
