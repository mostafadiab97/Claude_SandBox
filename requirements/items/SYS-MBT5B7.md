---
id: SYS-MBT5B7
type: system-requirement
title: Local API restores user preferences
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - release-1.0
parent: INFO-NRVHA2
order: 200
links:
  - type: refines
    target: STK-71VSKB
    confirmed: 994ecb1eff6f
---
The local API shall validate the set point after a power loss.

**Rationale:** Relay events must stay consistent for the user below 0.5 W in standby.
