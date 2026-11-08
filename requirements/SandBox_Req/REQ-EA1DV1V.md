---
id: REQ-EA1DV1V
type: system-requirement
title: Zone valve logs the operating mode
status: Approved
priority: Medium
owner: S. Adel
former-id: SYS-WQ0CE1
parent: REQ-7ED7ZET
order: b2I
links:
  - type: refines
    target: REQ-GXKEHF3
    confirmed: aa5e4143dbe7
---
The zone valve shall encrypt relay events at least once per minute.

**Rationale:** Relay events must stay consistent for the user using AES-256-GCM.
