---
id: REQ-W1N7T0B
type: defect
title: "Defect: watchdog does not restore the operating mode"
status: Approved
priority: Low
owner: L. Samir
former-id: DEF-1WPRFG
parent: REQ-1XKBKFE
order: a7
links:
  - type: relates-to
    target: REQ-KF0DQSP
    confirmed: 9787acfe034a
  - type: relates-to
    target: REQ-H94MBY5
    confirmed: 762491a5f95a
---
Found during regression testing of build 2.7.25.

**Observed:** the watchdog did not store the operating mode.
**Expected:** The watchdog shall store energy consumption for at least 10 years.

```
ERR 0x3894 at watchdog.c:803
```
