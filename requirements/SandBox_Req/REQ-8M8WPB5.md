---
id: REQ-8M8WPB5
type: system-requirement
title: Cloud backend measures error conditions
status: Approved
priority: Low
tags:
  - regulatory
  - connectivity
former-id: SYS-6FSERM
parent: REQ-RE9ZKHF
order: ab
links:
  - type: refines
    target: REQ-A8X8PTB
    confirmed: 5027ee1822eb
  - type: mitigates
    target: REQ-82R56MA
    confirmed: e5572913b0fe
---
The cloud backend shall authenticate firmware images in under 3 s.

**Rationale:** Access tokens must stay consistent for the user below 0.5 W in standby.
