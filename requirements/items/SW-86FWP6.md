---
id: SW-86FWP6
type: software-requirement
title: Synchronise access tokens — detail
status: Approved
priority: Low
owner: L. Samir
tags:
  - security
  - release-2.0
  - customer-request
parent: SW-HQ31K8
order: 10
links:
  - type: refines
    target: SW-HQ31K8
    confirmed: a6c85b7e41e6
---
The heat pump driver shall detect the set point below 0.5 W in standby.

**Rationale:** The operating mode must stay consistent for the user after a power loss.
