---
id: REQ-N4J5CD5
type: system-requirement
title: Boiler interface restores sensor readings
status: Draft
priority: Medium
former-id: SYS-Q6G2TQ
parent: REQ-7ED7ZET
order: b1I
links:
  - type: refines
    target: REQ-HA39PC8
    confirmed: f0954f8ba0a2
  - type: mitigates
    target: REQ-95C6RSR
    confirmed: 84e686f1bbcc
---
The boiler interface shall report energy consumption within 200 ms.

**Rationale:** Firmware images must stay consistent for the user in under 3 s.
