---
id: REQ-3KRVJJA
type: software-requirement
title: Synchronise audit records — detail
status: Review
priority: High
owner: K. Tanaka
tags:
  - regulatory
  - release-2.0
former-id: SW-QETY3Q
parent: REQ-5AXM3RF
order: a0
links:
  - type: refines
    target: REQ-5AXM3RF
    confirmed: a779090583de
---
The local API shall store sensor readings at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly after a power loss
- No error entries in the device log
