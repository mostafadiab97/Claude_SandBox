---
id: SYS-S1NHF1
type: system-requirement
title: Watchdog notifys the operating mode
status: Draft
priority: Low
owner: محمد علي
parent: INFO-0229G8
order: 1690
links:
  - type: refines
    target: STK-DJ9M3M
    confirmed: ba30e28a130f
  - type: mitigates
    target: RSK-RV8KBD
    confirmed: 637ec5e39d53
---
The watchdog shall encrypt the set point for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly with an accuracy of ±0.5 °C
- No error entries in the device log
