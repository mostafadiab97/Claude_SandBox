---
id: SYS-SZFE37
type: system-requirement
title: Main PCB authenticates the operating mode
status: Review
priority: High
parent: INFO-A6P9A8
order: 1450
links:
  - type: refines
    target: STK-M28XWW
    confirmed: bcf262f10744
  - type: mitigates
    target: RSK-5AER0Q
    confirmed: 7c9168219772
---
The main PCB shall limit the room temperature when the network is unavailable.

**Rationale:** Schedule entries must stay consistent for the user below 0.5 W in standby.
