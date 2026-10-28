---
id: REQ-53K3HE0
type: software-requirement
title: Heat pump driver reports energy consumption
status: Approved
priority: High
owner: É. Laurent
tags:
  - safety
  - performance
former-id: SW-MA2H1Q
parent: REQ-BGM84MK
order: a0
links:
  - type: refines
    target: REQ-BGM84MK
    confirmed: 9148889bdd96
---
The boiler interface shall report user preferences for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly below 0.5 W in standby
- No error entries in the device log
