---
id: REQ-KPAPEVJ
type: software-requirement
title: Local API measures humidity values
status: Review
priority: Low
owner: É. Laurent
former-id: SW-0KPY3S
parent: REQ-4TTQQT5
order: a1
links:
  - type: refines
    target: REQ-4TTQQT5
    confirmed: cb86cdc33269
---
The local API shall measure safety limits in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly when the network is unavailable
- No error entries in the device log
