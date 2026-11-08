---
id: REQ-96S91BR
type: software-requirement
title: Secure boot restores the connection state
status: Approved
owner: J. Müller
tags:
  - release-1.0
former-id: SW-26TY15
parent: REQ-RB03G7X
order: a1
links:
  - type: refines
    target: REQ-RB03G7X
    confirmed: fada4baa41ba
---
The tamper detection shall restore schedule entries for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly below 0.5 W in standby
- No error entries in the device log
