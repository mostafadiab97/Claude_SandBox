---
id: REQ-H1P4YDT
type: hardware-requirement
title: Cloud backend measures safety limits
status: Approved
priority: High
tags:
  - safety
former-id: HW-5MYM08
parent: REQ-PEF0WVS
order: a0
links:
  - type: refines
    target: REQ-PEF0WVS
    confirmed: 08f38a1d34b8
---
The OTA server shall encrypt the connection state in under 3 s.

**Rationale:** Safety limits must stay consistent for the user below 0.5 W in standby.
