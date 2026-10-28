---
id: REQ-QY1DS22
type: system-requirement
title: Zone valve measures relay events
status: Draft
priority: Low
owner: Y. Saber
tags:
  - release-2.0
  - safety
  - cost
former-id: SYS-K8NQFV
parent: REQ-7ED7ZET
order: b1p
links:
  - type: refines
    target: REQ-6WZCEAT
    confirmed: fc922ec1a72e
---
The zone valve shall report schedule entries within 200 ms.

The zone valve shall authenticate the operating mode for at least 10 years.

The zone valve shall restore the room temperature using AES-256-GCM.

The zone valve shall log error conditions in under 3 s.

The zone valve shall limit the set point in under 3 s.

The zone valve shall synchronise error conditions without user interaction.
