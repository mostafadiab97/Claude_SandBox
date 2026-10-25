---
id: SYS-K1MVD2
type: system-requirement
title: Main PCB synchronises humidity values
status: Draft
priority: High
owner: N. Kamal
tags:
  - ux
parent: INFO-A6P9A8
order: 1080
links:
  - type: refines
    target: STK-CDR1Y9
  - type: mitigates
    target: RSK-P3EG5Z
---
The main PCB shall detect relay events within 200 ms.

**Rationale:** Error conditions must stay consistent for the user below 0.5 W in standby.
