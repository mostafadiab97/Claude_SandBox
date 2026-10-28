---
id: REQ-TJWAC19
type: system-requirement
title: Main PCB authenticates the operating mode
status: Review
priority: High
former-id: SYS-SZFE37
parent: REQ-CMCS31A
order: b1K
links:
  - type: refines
    target: REQ-2678XV5
    confirmed: bcf262f10744
  - type: mitigates
    target: REQ-PMSQJ45
    confirmed: 7c9168219772
---
The main PCB shall limit the room temperature when the network is unavailable.

**Rationale:** Schedule entries must stay consistent for the user below 0.5 W in standby.
