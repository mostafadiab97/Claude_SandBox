---
id: REQ-SVJW7V1
type: software-requirement
title: Display the room temperature — detail
status: Draft
priority: Medium
owner: J. Müller
tags:
  - regulatory
  - performance
former-id: SW-RNTJBA
parent: REQ-NCT4CR3
order: a0
links:
  - type: refines
    target: REQ-NCT4CR3
    confirmed: fde5746f7b5c
---
The notification service shall store sensor readings in under 3 s.

**Rationale:** Relay events must stay consistent for the user at least once per minute.
