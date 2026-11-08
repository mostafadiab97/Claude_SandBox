---
id: REQ-RBB80A5
type: interface-requirement
title: Battery backup calibrates the connection state
status: Draft
priority: Medium
owner: É. Laurent
former-id: IF-QW1A3Z
parent: REQ-CR8428R
order: a1
links:
  - type: refines
    target: REQ-CR8428R
    confirmed: 257707a82d4d
---
The enclosure shall detect relay events below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly in under 3 s
- No error entries in the device log
