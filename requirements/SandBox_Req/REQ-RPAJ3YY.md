---
id: REQ-RPAJ3YY
type: system-requirement
title: Mobile app encrypts the set point
status: Approved
priority: Low
owner: J. Müller
former-id: SYS-Z9T7JH
parent: REQ-QYXGSQ4
order: b29
links:
  - type: refines
    target: REQ-AC08V5H
    confirmed: cf78baefa376
  - type: mitigates
    target: REQ-0CSS0FS
    confirmed: fdb267eb1465
---
The mobile app shall authenticate access tokens with an accuracy of ±0.5 °C.

**Rationale:** Sensor readings must stay consistent for the user for up to 8 zones.
