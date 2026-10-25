---
id: DEF-JN6JQ7
type: defect
title: "Defect: touch display does not encrypt schedule entries"
status: Draft
tags:
  - security
  - regulatory
parent: INFO-7HY7F9
order: 60
links:
  - type: relates-to
    target: TC-S0X8X9
    confirmed: 4c3efeb79f14
  - type: relates-to
    target: SYS-TB9F0A
    confirmed: cfce1cacc944
---
Found during regression testing of build 2.0.34.

**Observed:** the touch display did not restore firmware images.
**Expected:** The touch display shall store relay events after a power loss.

```
ERR 0x6163 at touch_display.c:282
```
