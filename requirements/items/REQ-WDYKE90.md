---
id: REQ-WDYKE90
type: software-requirement
title: Schedule editor stores the set point
status: Draft
priority: High
owner: K. Tanaka
tags:
  - EMC
  - power
  - accessibility
former-id: SW-T5QVCQ
parent: REQ-M6ARR9M
order: a0
links:
  - type: refines
    target: REQ-M6ARR9M
    confirmed: 846402a4433f
---
The schedule editor shall restore the operating mode within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly after a power loss
- No error entries in the device log
