---
id: DEF-XFSBBS
type: defect
title: "Defect: touch display does not display sensor readings"
status: Draft
priority: Medium
owner: محمد علي
parent: INFO-7HY7F9
order: 180
links:
  - type: relates-to
    target: TC-7TQASG
  - type: relates-to
    target: SYS-56D65V
---
Found during regression testing of build 2.8.31.

**Observed:** the touch display did not synchronise user preferences.
**Expected:** The touch display shall display safety limits when the network is unavailable.

```
ERR 0x1bb6 at touch_display.c:316
```
