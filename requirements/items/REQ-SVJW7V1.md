---
id: SW-RNTJBA
type: software-requirement
title: Display the room temperature — detail
status: Draft
priority: Medium
owner: J. Müller
tags:
  - regulatory
  - performance
parent: SW-MZ2CT7
order: 10
links:
  - type: refines
    target: SW-MZ2CT7
    confirmed: fde5746f7b5c
---
The notification service shall store sensor readings in under 3 s.

**Rationale:** Relay events must stay consistent for the user at least once per minute.
