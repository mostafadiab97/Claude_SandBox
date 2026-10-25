---
id: DEF-26KYRM
type: defect
title: "Defect: zone valve does not detect access tokens"
status: Approved
priority: Medium
tags:
  - connectivity
parent: INFO-ZBHTYF
order: 60
links:
  - type: relates-to
    target: TC-GGJPK4
    confirmed: 3b544ee1feb7
  - type: relates-to
    target: SYS-185CG5
    confirmed: 594be3c2d403
---
Found during regression testing of build 2.3.22.

**Observed:** the zone valve did not limit the set point.
**Expected:** The zone valve shall report user preferences after a power loss.

```
ERR 0x0b7f at zone_valve.c:883
```
