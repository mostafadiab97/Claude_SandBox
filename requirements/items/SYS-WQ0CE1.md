---
id: SYS-WQ0CE1
type: system-requirement
title: Zone valve logs the operating mode
status: Approved
priority: Medium
owner: S. Adel
parent: INFO-6DQTKV
order: 2050
links:
  - type: refines
    target: STK-EWSQ9Z
---
The zone valve shall encrypt relay events at least once per minute.

**Rationale:** Relay events must stay consistent for the user using AES-256-GCM.
