---
id: SYS-BT3DXG
type: system-requirement
title: Watchdog stores sensor readings
status: Approved
priority: Low
owner: H. Mostafa
parent: INFO-0229G8
order: 820
links:
  - type: refines
    target: STK-92HHJV
    confirmed: 260bd01800c6
---
The watchdog shall limit audit records in under 3 s.

**Rationale:** Access tokens must stay consistent for the user below 0.5 W in standby.
