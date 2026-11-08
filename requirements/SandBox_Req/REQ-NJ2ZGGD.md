---
id: REQ-NJ2ZGGD
type: software-requirement
title: Wi-Fi module encrypts error conditions
status: Review
priority: Medium
owner: N. Kamal
former-id: SW-37QCGC
parent: REQ-VP326G6
order: a2
links:
  - type: refines
    target: REQ-VP326G6
    confirmed: 7ffa04910a1e
---
The pairing process shall encrypt error conditions below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly when the network is unavailable
- No error entries in the device log
