---
id: REQ-H1WT401
type: defect
title: "Defect: zone valve does not detect access tokens"
status: Approved
priority: Medium
tags:
  - connectivity
former-id: DEF-26KYRM
parent: REQ-XJDN42Y
order: a5
links:
  - type: relates-to
    target: REQ-4XD749P
    confirmed: 3b544ee1feb7
  - type: relates-to
    target: REQ-EJYJMP4
    confirmed: 594be3c2d403
---
Found during regression testing of build 2.3.22.

**Observed:** the zone valve did not limit the set point.
**Expected:** The zone valve shall report user preferences after a power loss.

```
ERR 0x0b7f at zone_valve.c:883
```
