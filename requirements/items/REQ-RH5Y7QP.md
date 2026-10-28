---
id: REQ-RH5Y7QP
type: hardware-requirement
title: Encryption layer detects the connection state
status: Draft
priority: Low
former-id: HW-G6WN2X
parent: REQ-8V3JXAY
order: a2
links:
  - type: refines
    target: REQ-8V3JXAY
    confirmed: c483239675ae
---
The over-temperature monitor shall authenticate the connection state when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly without user interaction
- No error entries in the device log
