---
id: DEF-HF9SVF
type: defect
title: "Defect: watchdog does not calibrate relay events"
status: Review
owner: محمد علي
tags:
  - release-2.0
parent: INFO-6QFMYN
order: 100
links:
  - type: relates-to
    target: TC-BZFCE0
    confirmed: e17c2ae77fd1
  - type: relates-to
    target: SYS-WKCZDQ
    confirmed: ef7ce1eb28d3
---
Found during regression testing of build 2.3.3.

**Observed:** the watchdog did not encrypt error conditions.
**Expected:** The watchdog shall display humidity values in under 3 s.

```
ERR 0x7c5d at watchdog.c:255
```
