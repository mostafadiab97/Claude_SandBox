---
id: REQ-3ZM1N85
type: system-requirement
title: Watchdog synchronises schedule entries
status: Review
owner: É. Laurent
former-id: SYS-RGCFDP
parent: REQ-H9113WA
order: b1n
links:
  - type: refines
    target: REQ-Z7761RK
    confirmed: 260bd01800c6
---
The watchdog shall synchronise audit records using AES-256-GCM.

**Rationale:** The room temperature must stay consistent for the user using AES-256-GCM.
