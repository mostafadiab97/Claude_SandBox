---
id: IF-0QHZ3N
type: interface-requirement
title: Schedule editor restores the operating mode
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - customer-request
  - EMC
parent: SYS-TE4YGF
order: 10
links:
  - type: refines
    target: SYS-TE4YGF
    confirmed: 7a16860169f9
---
The schedule editor shall notify schedule entries within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly after a power loss
- No error entries in the device log
