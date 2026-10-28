---
id: REQ-19KQDTF
type: hardware-requirement
title: Notify schedule entries — detail
status: Review
priority: Low
owner: R. Nabil
tags:
  - release-2.0
former-id: HW-BS2DR5
parent: REQ-C8EKT78
order: a0
links:
  - type: refines
    target: REQ-C8EKT78
    confirmed: 16d828a121d5
---
The device registry shall notify access tokens when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly using AES-256-GCM
- No error entries in the device log
