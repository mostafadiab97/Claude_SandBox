---
id: REQ-QDG4A41
type: interface-requirement
title: Relay board limits the connection state
status: Draft
priority: Medium
owner: É. Laurent
tags:
  - accessibility
  - security
former-id: IF-E3YFM9
parent: REQ-E7EV6P4
order: a0
links:
  - type: refines
    target: REQ-E7EV6P4
    confirmed: fd85d789dbcd
---
The main PCB shall detect the set point within 200 ms.

**Rationale:** Relay events must stay consistent for the user with an accuracy of ±0.5 °C.
