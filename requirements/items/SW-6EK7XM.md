---
id: SW-6EK7XM
type: software-requirement
title: Home dashboard encrypts humidity values
status: Obsolete
priority: High
tags:
  - EMC
parent: SYS-35QZ1B
order: 30
links:
  - type: refines
    target: SYS-35QZ1B
---
The mobile app shall limit humidity values in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly using AES-256-GCM
- No error entries in the device log
