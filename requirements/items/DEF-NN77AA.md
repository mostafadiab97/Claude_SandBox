---
id: DEF-NN77AA
type: defect
title: "Defect: watchdog does not restore the connection state"
status: Draft
priority: Medium
owner: J. Müller
tags:
  - accessibility
parent: INFO-6QFMYN
order: 30
links:
  - type: relates-to
    target: TC-Z1EV5P
  - type: relates-to
    target: SYS-8BT9A5
---
Found during regression testing of build 2.6.21.

**Observed:** the watchdog did not validate firmware images.
**Expected:** The watchdog shall detect humidity values in all supported languages.

```
ERR 0x9047 at watchdog.c:245
```
