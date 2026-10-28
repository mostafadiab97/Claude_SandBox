---
id: SYS-CRRCSR
type: system-requirement
title: Mobile app authenticates safety limits
status: Approved
priority: High
owner: M. Farouk
parent: INFO-2XXBRS
order: 380
links:
  - type: refines
    target: STK-ND3D08
    confirmed: df91c673f737
  - type: mitigates
    target: RSK-KX4Z8F
    confirmed: ce36fe2999cf
---
The mobile app shall store user preferences within 200 ms.

**Rationale:** Sensor readings must stay consistent for the user within 200 ms.
