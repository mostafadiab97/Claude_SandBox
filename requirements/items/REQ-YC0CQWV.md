---
id: REQ-YC0CQWV
type: defect
title: "Defect: home dashboard does not validate safety limits"
status: Approved
priority: Medium
tags:
  - connectivity
  - safety
former-id: DEF-FWNEY9
parent: REQ-MWRPGWA
order: a5
links:
  - type: relates-to
    target: REQ-1Q7X9M4
    confirmed: c4ff7a1d709c
  - type: relates-to
    target: REQ-QV0A247
    confirmed: "131852556952"
---
Found during regression testing of build 2.6.7.

**Observed:** the home dashboard did not encrypt the room temperature.
**Expected:** The home dashboard shall store the room temperature for up to 8 zones.

```
ERR 0xec19 at home_dashboard.c:830
```
