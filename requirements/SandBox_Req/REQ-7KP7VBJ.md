---
id: REQ-7KP7VBJ
type: defect
title: "Defect: watchdog does not encrypt humidity values"
status: Approved
priority: High
owner: A. Hassan
tags:
  - performance
former-id: DEF-55G3F4
parent: REQ-1XKBKFE
order: aH
links:
  - type: relates-to
    target: REQ-EPB8RTF
    confirmed: f37fa41af6c6
  - type: relates-to
    target: REQ-J7S8BCM
    confirmed: c1cdb8e3bdac
---
Found during regression testing of build 2.0.15.

**Observed:** the watchdog did not detect safety limits.
**Expected:** The watchdog shall encrypt schedule entries below 0.5 W in standby.

```
ERR 0xb7fb at watchdog.c:381
```
