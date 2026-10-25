---
id: DEF-55G3F4
type: defect
title: "Defect: watchdog does not encrypt humidity values"
status: Approved
priority: High
owner: A. Hassan
tags:
  - performance
parent: INFO-6QFMYN
order: 180
links:
  - type: relates-to
    target: TC-XPQ955
  - type: relates-to
    target: SYS-H824VB
---
Found during regression testing of build 2.0.15.

**Observed:** the watchdog did not detect safety limits.
**Expected:** The watchdog shall encrypt schedule entries below 0.5 W in standby.

```
ERR 0xb7fb at watchdog.c:381
```
