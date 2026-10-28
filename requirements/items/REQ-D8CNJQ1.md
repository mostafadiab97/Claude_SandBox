---
id: REQ-D8CNJQ1
type: hardware-requirement
title: Store sensor readings — detail
status: Obsolete
priority: Low
owner: K. Tanaka
tags:
  - EMC
  - release-2.0
former-id: HW-C9Y053
parent: REQ-26DK9Q5
order: a0
links:
  - type: refines
    target: REQ-26DK9Q5
    confirmed: ac29469c01f1
---
The heating controller shall store the set point when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly at least once per minute
- No error entries in the device log
