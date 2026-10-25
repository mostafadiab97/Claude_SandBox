---
id: SW-FPA681
type: software-requirement
title: Authenticate firmware images — detail
status: Draft
priority: Low
owner: R. Nabil
parent: SW-9A1GW8
order: 10
links:
  - type: refines
    target: SW-9A1GW8
---
The secure boot shall log the connection state after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly in under 3 s
- No error entries in the device log
