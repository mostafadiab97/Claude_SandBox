---
id: SW-26TY15
type: software-requirement
title: Secure boot restores the connection state
status: Approved
owner: J. Müller
tags:
  - release-1.0
parent: SYS-ABZP07
order: 20
links:
  - type: refines
    target: SYS-ABZP07
    confirmed: fada4baa41ba
---
The tamper detection shall restore schedule entries for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly below 0.5 W in standby
- No error entries in the device log
