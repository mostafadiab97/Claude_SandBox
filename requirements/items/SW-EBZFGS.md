---
id: SW-EBZFGS
type: software-requirement
title: Notify firmware images — detail
status: Draft
priority: Medium
owner: محمد علي
tags:
  - safety
  - performance
parent: SW-S9VAGC
order: 10
links:
  - type: refines
    target: SW-S9VAGC
    confirmed: 68b2b15ce1a7
---
The regulation loop shall restore safety limits after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly below 0.5 W in standby
- No error entries in the device log
