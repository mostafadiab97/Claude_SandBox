---
id: SW-T6028K
type: software-requirement
title: Watchdog validates sensor readings
status: Approved
priority: Low
owner: K. Tanaka
parent: SYS-T2DEWW
order: 30
links:
  - type: refines
    target: SYS-T2DEWW
    confirmed: 4c2247349bae
---
The watchdog shall notify the operating mode with an accuracy of ±0.5 °C.

**Rationale:** Humidity values must stay consistent for the user within 200 ms.
