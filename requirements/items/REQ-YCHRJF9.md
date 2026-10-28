---
id: REQ-YCHRJF9
type: hardware-requirement
title: Enclosure reports the set point
status: Review
priority: High
owner: محمد علي
tags:
  - security
  - regulatory
former-id: HW-FKM413
parent: REQ-E29MYCT
order: a0
links:
  - type: refines
    target: REQ-E29MYCT
    confirmed: 9b2c415b0097
---
The main PCB shall measure the set point using AES-256-GCM.

**Rationale:** The set point must stay consistent for the user within 200 ms.
