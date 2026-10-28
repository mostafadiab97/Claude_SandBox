---
id: REQ-V85S0DH
type: software-requirement
title: Encryption layer synchronises audit records
status: Approved
priority: Medium
owner: Y. Saber
former-id: SW-R97F3W
parent: REQ-GFFZN3Z
order: a3
links:
  - type: refines
    target: REQ-GFFZN3Z
    confirmed: 3f8b6bcfec69
---
The tamper detection shall report schedule entries using AES-256-GCM.

**Rationale:** Energy consumption must stay consistent for the user at least once per minute.
