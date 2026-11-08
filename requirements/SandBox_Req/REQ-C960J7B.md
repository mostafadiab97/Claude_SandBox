---
id: REQ-C960J7B
type: hardware-requirement
title: Power supply detects error conditions
status: Approved
priority: Medium
owner: É. Laurent
former-id: HW-R30PP1
parent: REQ-QCJ3WMP
order: a1
links:
  - type: refines
    target: REQ-QCJ3WMP
    confirmed: 1d8cfb08af6f
---
The enclosure shall notify relay events when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly within 200 ms
- No error entries in the device log
