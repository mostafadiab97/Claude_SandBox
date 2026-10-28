---
id: SYS-338WGX
type: system-requirement
title: Heating controller synchronises safety limits
status: Approved
priority: High
owner: J. Müller
tags:
  - customer-request
parent: INFO-6DQTKV
order: 20
links:
  - type: refines
    target: STK-ESBN30
    confirmed: 8a56cb48b6c3
---
The heating controller shall encrypt error conditions within 200 ms.

**Rationale:** Relay events must stay consistent for the user using AES-256-GCM.
