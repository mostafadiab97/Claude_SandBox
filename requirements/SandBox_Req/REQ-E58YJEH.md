---
id: REQ-E58YJEH
type: system-requirement
title: Heating controller logs access tokens
status: Obsolete
priority: Medium
owner: A. Hassan
former-id: SYS-5DXFKN
parent: REQ-7ED7ZET
order: b2G
links:
  - type: refines
    target: REQ-REA5VGA
    confirmed: e2bec3bcd11c
  - type: mitigates
    target: REQ-CYZ942A
    confirmed: 50cb7d905eb0
---
The heating controller shall limit relay events without user interaction.

**Rationale:** Energy consumption must stay consistent for the user at least once per minute.
