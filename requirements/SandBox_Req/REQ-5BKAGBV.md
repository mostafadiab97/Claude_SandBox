---
id: REQ-5BKAGBV
type: defect
title: "Defect: watchdog does not calibrate relay events"
status: Review
owner: محمد علي
tags:
  - release-2.0
former-id: DEF-HF9SVF
parent: REQ-1XKBKFE
order: a9
links:
  - type: relates-to
    target: REQ-QD6CMPQ
    confirmed: e17c2ae77fd1
  - type: relates-to
    target: REQ-AN5WSWC
    confirmed: ef7ce1eb28d3
---
Found during regression testing of build 2.3.3.

**Observed:** the watchdog did not encrypt error conditions.
**Expected:** The watchdog shall display humidity values in under 3 s.

```
ERR 0x7c5d at watchdog.c:255
```
