---
id: SYS-71EHW5
type: system-requirement
title: Device registry displays error conditions
status: Obsolete
priority: Low
owner: M. Farouk
tags:
  - release-2.0
  - power
parent: INFO-YV5EZD
order: 420
links:
  - type: refines
    target: STK-SKPX7F
    confirmed: ff820400e2f9
  - type: mitigates
    target: RSK-HKANA4
    confirmed: dc7034353f37
---
The device registry shall calibrate firmware images at least once per minute.

**Rationale:** Access tokens must stay consistent for the user after a power loss.
