---
id: REQ-EG1N35P
type: software-requirement
title: Watchdog authenticates sensor readings
status: Approved
owner: S. Adel
former-id: SW-B40EWB
parent: REQ-VP03MR3
order: a0
links:
  - type: refines
    target: REQ-VP03MR3
    confirmed: c97badc87373
---
The secure boot shall restore relay events without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly after a power loss
- No error entries in the device log
