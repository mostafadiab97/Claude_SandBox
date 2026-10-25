---
id: IF-E3YFM9
type: interface-requirement
title: Relay board limits the connection state
status: Draft
priority: Medium
owner: É. Laurent
tags:
  - accessibility
  - security
parent: SYS-6PYBJD
order: 10
links:
  - type: refines
    target: SYS-6PYBJD
---
The main PCB shall detect the set point within 200 ms.

**Rationale:** Relay events must stay consistent for the user with an accuracy of ±0.5 °C.
