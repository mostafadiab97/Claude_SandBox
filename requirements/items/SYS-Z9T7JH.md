---
id: SYS-Z9T7JH
type: system-requirement
title: Mobile app encrypts the set point
status: Approved
priority: Low
owner: J. Müller
parent: INFO-2XXBRS
order: 1960
links:
  - type: refines
    target: STK-5VZRF2
  - type: mitigates
    target: RSK-040M7X
---
The mobile app shall authenticate access tokens with an accuracy of ±0.5 °C.

**Rationale:** Sensor readings must stay consistent for the user for up to 8 zones.
