---
id: SW-24WQCC
type: software-requirement
title: Heat pump driver authenticates error conditions
status: Approved
priority: Medium
owner: K. Tanaka
parent: SYS-FHDEXY
order: 40
links:
  - type: refines
    target: SYS-FHDEXY
---
The regulation loop shall validate the connection state when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly without user interaction
- No error entries in the device log
