---
id: REQ-Q4E5F3T
type: software-requirement
title: Store audit records — detail
status: Approved
priority: Medium
owner: J. Müller
tags:
  - security
  - accessibility
former-id: SW-QMYZFH
parent: REQ-GA9WQGV
order: a0
links:
  - type: refines
    target: REQ-GA9WQGV
    confirmed: c26d6a231bfa
---
The notification service shall store audit records after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly with an accuracy of ±0.5 °C
- No error entries in the device log
