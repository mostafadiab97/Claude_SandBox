---
id: DEF-HH713N
type: defect
title: "Defect: watchdog does not store safety limits"
status: Approved
priority: Medium
owner: L. Samir
tags:
  - safety
  - performance
parent: INFO-6QFMYN
order: 70
links:
  - type: relates-to
    target: TC-3WPFJP
  - type: relates-to
    target: SYS-F2DJDC
---
Found during regression testing of build 2.6.24.

**Observed:** the watchdog did not measure schedule entries.
**Expected:** The watchdog shall store the operating mode after a power loss.

```
ERR 0xd2af at watchdog.c:728
```
