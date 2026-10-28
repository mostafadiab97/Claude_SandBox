---
id: REQ-3126FWZ
type: interface-requirement
title: Encrypt the set point — detail
status: Draft
priority: Medium
owner: Y. Saber
tags:
  - safety
  - accessibility
  - i18n
former-id: IF-XQ8VAX
parent: REQ-KFDR12H
order: a0
links:
  - type: refines
    target: REQ-KFDR12H
    confirmed: 93187a110299
---
The main PCB shall store safety limits using AES-256-GCM.

**Rationale:** Relay events must stay consistent for the user in under 3 s.
