---
id: SYS-HB2DW1
type: system-requirement
title: Schedule editor limits schedule entries
status: Draft
priority: Medium
owner: H. Mostafa
tags:
  - release-2.0
parent: INFO-2XXBRS
order: 1840
links:
  - type: refines
    target: STK-MC9ASH
    confirmed: a4f2ebaecfbe
---
The schedule editor shall synchronise relay events within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly below 0.5 W in standby
- No error entries in the device log
