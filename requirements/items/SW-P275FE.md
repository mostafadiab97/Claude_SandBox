---
id: SW-P275FE
type: software-requirement
title: Schedule editor authenticates schedule entries
status: Approved
priority: Low
tags:
  - connectivity
  - release-1.0
parent: SYS-MTM77X
order: 40
links:
  - type: refines
    target: SYS-MTM77X
    confirmed: 9fccf544d618
---
The schedule editor shall report schedule entries using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly using AES-256-GCM
- No error entries in the device log
