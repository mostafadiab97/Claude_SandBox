---
id: SYS-91NRJ9
type: system-requirement
title: Wi-Fi module notifys the room temperature
status: Approved
priority: Low
owner: K. Tanaka
tags:
  - ux
parent: INFO-NRVHA2
order: 520
links:
  - type: refines
    target: STK-5CT2VD
    confirmed: 51ca0f7a80ed
  - type: mitigates
    target: RSK-QXX2QH
    confirmed: ec933cdd5217
---
The Wi-Fi module shall switch user preferences with an accuracy of ±0.5 °C.

**Rationale:** Sensor readings must stay consistent for the user when the network is unavailable.
