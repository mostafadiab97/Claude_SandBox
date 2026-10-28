---
id: REQ-G0JDVZR
type: hardware-requirement
title: Main PCB measures humidity values
status: Review
priority: Medium
owner: M. Farouk
tags:
  - accessibility
  - release-1.0
  - security
former-id: HW-34S5C8
parent: REQ-NHG4VB7
order: a1
links:
  - type: refines
    target: REQ-NHG4VB7
    confirmed: 58f0d670cbc1
---
The main PCB shall log sensor readings using AES-256-GCM.

**Rationale:** Error conditions must stay consistent for the user when the network is unavailable.
