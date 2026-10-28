---
id: REQ-8PXEN9G
type: software-requirement
title: Regulation loop calibrates access tokens
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - performance
  - ux
former-id: SW-YBBSY4
parent: REQ-QZW142T
order: a1
links:
  - type: refines
    target: REQ-QZW142T
    confirmed: 450d9078b1b0
---
The regulation loop shall store the set point when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly below 0.5 W in standby
- No error entries in the device log
