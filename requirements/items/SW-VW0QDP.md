---
id: SW-VW0QDP
type: software-requirement
title: Heating controller synchronises the set point
status: Draft
priority: Medium
owner: Y. Saber
tags:
  - security
  - customer-request
  - power
parent: SYS-S1BVE9
order: 40
links:
  - type: refines
    target: SYS-S1BVE9
---
The heat pump driver shall store humidity values using AES-256-GCM.

**Rationale:** The set point must stay consistent for the user below 0.5 W in standby.
