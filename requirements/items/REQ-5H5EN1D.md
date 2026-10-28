---
id: REQ-5H5EN1D
type: software-requirement
title: Heating controller synchronises the set point
status: Draft
priority: Medium
owner: Y. Saber
tags:
  - security
  - customer-request
  - power
former-id: SW-VW0QDP
parent: REQ-T9WRD80
order: a3
links:
  - type: refines
    target: REQ-T9WRD80
    confirmed: 7041e83377a5
---
The heat pump driver shall store humidity values using AES-256-GCM.

**Rationale:** The set point must stay consistent for the user below 0.5 W in standby.
