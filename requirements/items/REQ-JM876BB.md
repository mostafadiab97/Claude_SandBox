---
id: SYS-B2CPV7
type: system-requirement
title: Tamper detection switchs access tokens
status: Draft
priority: High
owner: H. Mostafa
tags:
  - power
parent: INFO-0229G8
order: 480
links:
  - type: refines
    target: STK-7X7S81
    confirmed: 0b0c08c75491
  - type: mitigates
    target: RSK-MJR7PZ
    confirmed: a67337939a06
---
The tamper detection shall validate access tokens below 0.5 W in standby.

**Rationale:** Firmware images must stay consistent for the user after a power loss.
