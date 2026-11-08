---
id: REQ-08FGF89
type: hardware-requirement
title: Device registry calibrates energy consumption
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - regulatory
  - EMC
former-id: HW-HQCHQM
parent: REQ-4NAPSHQ
order: a1
links:
  - type: refines
    target: REQ-4NAPSHQ
    confirmed: 2507133e13d3
---
The telemetry pipeline shall display the set point within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly below 0.5 W in standby
- No error entries in the device log
