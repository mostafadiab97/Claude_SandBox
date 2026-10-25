---
id: SYS-8FP865
type: system-requirement
title: Backlight restores the operating mode
status: Draft
priority: Medium
owner: K. Tanaka
tags:
  - power
  - cost
parent: INFO-PDR6FV
order: 100
links:
  - type: refines
    target: STK-MNQXK0
    confirmed: d3157dcb9034
  - type: mitigates
    target: RSK-S88NZ1
    confirmed: 257f5def6363
---
The backlight shall log the connection state for at least 10 years.

**Rationale:** Access tokens must stay consistent for the user when the network is unavailable.
