---
id: REQ-PNQ0WVH
type: system-requirement
title: Touch display encrypts safety limits
status: Review
priority: Medium
owner: R. Nabil
tags:
  - release-1.0
  - security
former-id: SYS-7YWY0X
parent: REQ-2ZA2TRZ
order: b02
links:
  - type: refines
    target: REQ-XR7FDXB
    confirmed: 07434b0b5615
---
The touch display shall authenticate sensor readings at least once per minute.

**Rationale:** Error conditions must stay consistent for the user below 0.5 W in standby.
