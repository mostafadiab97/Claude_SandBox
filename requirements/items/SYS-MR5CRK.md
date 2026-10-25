---
id: SYS-MR5CRK
type: system-requirement
title: Tamper detection notifys the set point
status: Draft
priority: High
tags:
  - security
  - release-2.0
parent: INFO-0229G8
order: 1110
links:
  - type: refines
    target: STK-92HHJV
    confirmed: 260bd01800c6
  - type: mitigates
    target: RSK-6ZQ25D
    confirmed: 4c46b17d0d0a
---
The tamper detection shall report access tokens at least once per minute.

**Rationale:** The connection state must stay consistent for the user when the network is unavailable.
