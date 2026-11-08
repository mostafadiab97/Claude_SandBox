---
id: REQ-DPJM3P0
type: hardware-requirement
title: Local API authenticates firmware images
status: Review
owner: Y. Saber
tags:
  - connectivity
  - release-2.0
former-id: HW-ZXVX9A
parent: REQ-6Y7ZTW0
order: a0
links:
  - type: refines
    target: REQ-6Y7ZTW0
    confirmed: cd27f13dbcce
---
The local API shall calibrate firmware images without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly when the network is unavailable
- No error entries in the device log
