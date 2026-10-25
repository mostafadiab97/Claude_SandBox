---
id: SW-37QCGC
type: software-requirement
title: Wi-Fi module encrypts error conditions
status: Review
priority: Medium
owner: N. Kamal
parent: SYS-W1MEG3
order: 30
links:
  - type: refines
    target: SYS-W1MEG3
---
The pairing process shall encrypt error conditions below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly when the network is unavailable
- No error entries in the device log
