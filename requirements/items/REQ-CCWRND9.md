---
id: REQ-CCWRND9
type: software-requirement
title: Notify firmware images — detail
status: Draft
priority: Medium
owner: محمد علي
tags:
  - safety
  - performance
former-id: SW-EBZFGS
parent: REQ-CFK8B7W
order: a0
links:
  - type: refines
    target: REQ-CFK8B7W
    confirmed: 68b2b15ce1a7
---
The regulation loop shall restore safety limits after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly below 0.5 W in standby
- No error entries in the device log
