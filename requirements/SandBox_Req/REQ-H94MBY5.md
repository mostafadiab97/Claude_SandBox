---
id: REQ-H94MBY5
type: system-requirement
title: Watchdog stores sensor readings
status: Approved
priority: Low
owner: H. Mostafa
former-id: SYS-BT3DXG
parent: REQ-H9113WA
order: b0J
links:
  - type: refines
    target: REQ-Z7761RK
    confirmed: 260bd01800c6
---
The watchdog shall limit audit records in under 3 s.

**Rationale:** Access tokens must stay consistent for the user below 0.5 W in standby.
