---
id: SW-QETY3Q
type: software-requirement
title: Synchronise audit records — detail
status: Review
priority: High
owner: K. Tanaka
tags:
  - regulatory
  - release-2.0
parent: SW-NABSM9
order: 10
links:
  - type: refines
    target: SW-NABSM9
    confirmed: a779090583de
---
The local API shall store sensor readings at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly after a power loss
- No error entries in the device log
