---
id: REQ-ATDKWWH
type: software-requirement
title: Authenticate firmware images — detail
status: Draft
priority: Low
owner: R. Nabil
former-id: SW-FPA681
parent: REQ-ZNH71P6
order: a0
links:
  - type: refines
    target: REQ-ZNH71P6
    confirmed: 86e623abefc2
---
The secure boot shall log the connection state after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly in under 3 s
- No error entries in the device log
