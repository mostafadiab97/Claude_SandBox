---
id: IF-M7VMNS
type: interface-requirement
title: Tamper detection restores safety limits
status: Review
priority: High
owner: R. Nabil
tags:
  - EMC
  - security
parent: SYS-BHD8S6
order: 30
links:
  - type: refines
    target: SYS-BHD8S6
    confirmed: b4b9539a5d88
---
The encryption layer shall store audit records without user interaction.

**Rationale:** The set point must stay consistent for the user after a power loss.
