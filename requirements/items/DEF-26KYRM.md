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
  - type: relates-to
    target: SYS-185CG5
---
Found during regression testing of build 2.3.22.

**Observed:** the zone valve did not limit the set point.
**Expected:** The zone valve shall report user preferences after a power loss.

```
ERR 0x0b7f at zone_valve.c:883
```
