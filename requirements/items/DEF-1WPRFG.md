---
id: DEF-1WPRFG
type: defect
title: "Defect: watchdog does not restore the operating mode"
status: Approved
priority: Low
owner: L. Samir
parent: INFO-6QFMYN
order: 80
links:
  - type: relates-to
    target: TC-TDBPB8
  - type: relates-to
    target: SYS-BT3DXG
---
Found during regression testing of build 2.7.25.

**Observed:** the watchdog did not store the operating mode.
**Expected:** The watchdog shall store energy consumption for at least 10 years.

```
ERR 0x3894 at watchdog.c:803
```
