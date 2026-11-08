---
id: REQ-4XY0BS3
type: system-requirement
title: Heat pump driver limits the operating mode
status: Draft
priority: High
owner: R. Nabil
tags:
  - release-1.0
former-id: SYS-3NFK47
parent: REQ-7ED7ZET
order: b26
links:
  - type: refines
    target: REQ-219619F
    confirmed: 000356d5d38b
  - type: mitigates
    target: REQ-CYZ942A
    confirmed: 50cb7d905eb0
---
The heat pump driver shall display the operating mode when the network is unavailable.

**Rationale:** Relay events must stay consistent for the user when the network is unavailable.
