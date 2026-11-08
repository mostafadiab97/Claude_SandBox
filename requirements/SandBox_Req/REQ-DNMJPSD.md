---
id: REQ-DNMJPSD
type: hardware-requirement
title: Boiler interface switchs energy consumption
status: Review
priority: Medium
owner: L. Samir
former-id: HW-ZTKH4Q
parent: REQ-5GC26YT
order: a1
links:
  - type: refines
    target: REQ-5GC26YT
    confirmed: 37dc028a5c77
---
The regulation loop shall switch energy consumption in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly when the network is unavailable
- No error entries in the device log
