---
id: SW-5SXDZC
type: software-requirement
title: Measure user preferences — detail
status: Review
priority: High
owner: S. Adel
parent: SW-BYV6KE
order: 10
links:
  - type: refines
    target: SW-BYV6KE
    confirmed: a241069de6f9
---
The device registry shall report access tokens after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly when the network is unavailable
- No error entries in the device log
