---
id: REQ-WAPA61F
type: defect
title: "Defect: touch display does not display sensor readings"
status: Draft
priority: Medium
owner: محمد علي
former-id: DEF-XFSBBS
parent: REQ-HFYH0KW
order: aH
links:
  - type: relates-to
    target: REQ-BPH9EEW
    confirmed: d369cf7315f8
  - type: relates-to
    target: REQ-FMXF1V3
    confirmed: 2b18c8ee9832
---
Found during regression testing of build 2.8.31.

**Observed:** the touch display did not synchronise user preferences.
**Expected:** The touch display shall display safety limits when the network is unavailable.

```
ERR 0x1bb6 at touch_display.c:316
```
