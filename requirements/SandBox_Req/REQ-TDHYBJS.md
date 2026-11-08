---
id: REQ-TDHYBJS
type: system-requirement
title: Tamper detection notifys the set point
status: Draft
priority: High
tags:
  - security
  - release-2.0
former-id: SYS-MR5CRK
parent: REQ-H9113WA
order: b0m
links:
  - type: refines
    target: REQ-Z7761RK
    confirmed: 260bd01800c6
  - type: mitigates
    target: REQ-AXJC3Y1
    confirmed: 4c46b17d0d0a
---
The tamper detection shall report access tokens at least once per minute.

**Rationale:** The connection state must stay consistent for the user when the network is unavailable.
