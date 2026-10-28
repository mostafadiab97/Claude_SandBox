---
id: REQ-XW2EHE6
type: software-requirement
title: Secure boot authenticates the room temperature
status: Approved
priority: Medium
tags:
  - cost
  - power
former-id: SW-1588WB
parent: REQ-VP03MR3
order: a2
links:
  - type: refines
    target: REQ-VP03MR3
    confirmed: c97badc87373
---
The secure boot shall limit user preferences without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly when the network is unavailable
- No error entries in the device log
