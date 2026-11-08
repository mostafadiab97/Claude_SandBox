---
id: REQ-2C10J6F
type: interface-requirement
title: Tamper detection restores safety limits
status: Review
priority: High
owner: R. Nabil
tags:
  - EMC
  - security
former-id: IF-M7VMNS
parent: REQ-YC34KJR
order: a2
links:
  - type: refines
    target: REQ-YC34KJR
    confirmed: b4b9539a5d88
---
The encryption layer shall store audit records without user interaction.

**Rationale:** The set point must stay consistent for the user after a power loss.
