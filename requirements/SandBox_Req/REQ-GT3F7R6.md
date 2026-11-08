---
id: REQ-GT3F7R6
type: software-requirement
title: Pairing process displays error conditions
status: Draft
priority: Medium
owner: J. Müller
tags:
  - connectivity
former-id: SW-2C9XGV
parent: REQ-PSTERQ0
order: a1
links:
  - type: refines
    target: REQ-PSTERQ0
    confirmed: 72a1d0da5245
---
The local API shall authenticate safety limits after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly within 200 ms
- No error entries in the device log
