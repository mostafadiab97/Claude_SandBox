---
id: SW-XWK4WC
type: software-requirement
title: Synchronise the operating mode — detail
status: Review
priority: Medium
owner: É. Laurent
tags:
  - power
  - i18n
parent: SW-20QPSK
order: 10
links:
  - type: refines
    target: SW-20QPSK
    confirmed: 06b2cec7ac55
---
The encryption layer shall notify access tokens when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly in under 3 s
- No error entries in the device log
