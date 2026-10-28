---
id: REQ-DCD5QZB
type: defect
title: "Defect: watchdog does not restore the connection state"
status: Draft
priority: Medium
owner: J. Müller
tags:
  - accessibility
former-id: DEF-NN77AA
parent: REQ-1XKBKFE
order: a2
links:
  - type: relates-to
    target: REQ-J58B8QW
    confirmed: fa9fa55b5270
  - type: relates-to
    target: REQ-SNCRWC2
    confirmed: 768828fca553
---
Found during regression testing of build 2.6.21.

**Observed:** the watchdog did not validate firmware images.
**Expected:** The watchdog shall detect humidity values in all supported languages.

```
ERR 0x9047 at watchdog.c:245
```
