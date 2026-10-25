---
id: DEF-FWNEY9
type: defect
title: "Defect: home dashboard does not validate safety limits"
status: Approved
priority: Medium
tags:
  - connectivity
  - safety
parent: INFO-FH5FB3
order: 60
links:
  - type: relates-to
    target: TC-PAPJK4
    confirmed: c4ff7a1d709c
  - type: relates-to
    target: SYS-KE3ZCS
    confirmed: "131852556952"
---
Found during regression testing of build 2.6.7.

**Observed:** the home dashboard did not encrypt the room temperature.
**Expected:** The home dashboard shall store the room temperature for up to 8 zones.

```
ERR 0xec19 at home_dashboard.c:830
```
