---
id: REQ-43GSQBQ
type: software-requirement
title: Over-temperature monitor authenticates firmware images
status: Draft
priority: High
owner: K. Tanaka
former-id: SW-6F77QB
parent: REQ-7ENS3YJ
order: a1
links:
  - type: refines
    target: REQ-7ENS3YJ
    confirmed: ab26978cce76
---
The watchdog shall measure schedule entries in under 3 s.

**Rationale:** Sensor readings must stay consistent for the user at least once per minute.
