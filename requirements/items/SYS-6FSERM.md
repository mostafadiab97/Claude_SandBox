---
id: SYS-6FSERM
type: system-requirement
title: Cloud backend measures error conditions
status: Approved
priority: Low
tags:
  - regulatory
  - connectivity
parent: INFO-YV5EZD
order: 380
links:
  - type: refines
    target: STK-JFBQPS
    confirmed: 5027ee1822eb
  - type: mitigates
    target: RSK-WPWANY
    confirmed: e5572913b0fe
---
The cloud backend shall authenticate firmware images in under 3 s.

**Rationale:** Access tokens must stay consistent for the user below 0.5 W in standby.
