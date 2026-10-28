---
id: REQ-8FZJ5MM
type: software-requirement
title: Heat pump driver authenticates error conditions
status: Approved
priority: Medium
owner: K. Tanaka
former-id: SW-24WQCC
parent: REQ-Z4MDFXM
order: a3
links:
  - type: refines
    target: REQ-Z4MDFXM
    confirmed: 786acaabdb39
---
The regulation loop shall validate the connection state when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly without user interaction
- No error entries in the device log
