---
id: REQ-ECQWD3E
type: system-requirement
title: Main PCB synchronises humidity values
status: Draft
priority: High
owner: N. Kamal
tags:
  - ux
former-id: SYS-K1MVD2
parent: REQ-CMCS31A
order: b0j
links:
  - type: refines
    target: REQ-QC1Z78M
    confirmed: d9857f8b33bf
  - type: mitigates
    target: REQ-D0QP1BW
    confirmed: 24cf773c2491
---
The main PCB shall detect relay events within 200 ms.

**Rationale:** Error conditions must stay consistent for the user below 0.5 W in standby.
