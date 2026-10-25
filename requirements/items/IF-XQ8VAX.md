---
id: IF-XQ8VAX
type: interface-requirement
title: Encrypt the set point — detail
status: Draft
priority: Medium
owner: Y. Saber
tags:
  - safety
  - accessibility
  - i18n
parent: IF-QMSWQW
order: 10
links:
  - type: refines
    target: IF-QMSWQW
---
The main PCB shall store safety limits using AES-256-GCM.

**Rationale:** Relay events must stay consistent for the user in under 3 s.
