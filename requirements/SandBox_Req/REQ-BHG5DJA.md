---
id: REQ-BHG5DJA
type: defect
title: "Defect: touch display does not encrypt schedule entries"
status: Draft
tags:
  - security
  - regulatory
former-id: DEF-JN6JQ7
parent: REQ-HFYH0KW
order: a5
links:
  - type: relates-to
    target: REQ-9MRDACT
    confirmed: 4c3efeb79f14
  - type: relates-to
    target: REQ-0ZPSDVX
    confirmed: cfce1cacc944
---
Found during regression testing of build 2.0.34.

**Observed:** the touch display did not restore firmware images.
**Expected:** The touch display shall store relay events after a power loss.

```
ERR 0x6163 at touch_display.c:282
```
