---
id: REQ-5SMVJCZ
type: defect
title: "Defect: watchdog does not store safety limits"
status: Approved
priority: Medium
owner: L. Samir
tags:
  - safety
  - performance
former-id: DEF-HH713N
parent: REQ-1XKBKFE
order: a6
links:
  - type: relates-to
    target: REQ-FE0P08K
    confirmed: 73843db0166e
  - type: relates-to
    target: REQ-W18RFR4
    confirmed: 2d379fb34255
---
Found during regression testing of build 2.6.24.

**Observed:** the watchdog did not measure schedule entries.
**Expected:** The watchdog shall store the operating mode after a power loss.

```
ERR 0xd2af at watchdog.c:728
```
