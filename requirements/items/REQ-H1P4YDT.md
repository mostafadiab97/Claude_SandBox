---
id: HW-5MYM08
type: hardware-requirement
title: Cloud backend measures safety limits
status: Approved
priority: High
tags:
  - safety
parent: SYS-DRG6R3
order: 10
links:
  - type: refines
    target: SYS-DRG6R3
    confirmed: 08f38a1d34b8
---
The OTA server shall encrypt the connection state in under 3 s.

**Rationale:** Safety limits must stay consistent for the user below 0.5 W in standby.
