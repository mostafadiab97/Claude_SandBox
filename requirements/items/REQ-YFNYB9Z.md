---
id: REQ-YFNYB9Z
type: software-requirement
title: Watchdog validates sensor readings
status: Approved
priority: Low
owner: K. Tanaka
former-id: SW-T6028K
parent: REQ-84GVBQD
order: a2
links:
  - type: refines
    target: REQ-84GVBQD
    confirmed: 4c2247349bae
---
The watchdog shall notify the operating mode with an accuracy of ±0.5 °C.

**Rationale:** Humidity values must stay consistent for the user within 200 ms.
