---
id: REQ-54CNREE
type: defect
title: "Defect: touch display does not restore energy consumption"
status: Approved
priority: Medium
owner: S. Adel
tags:
  - ux
  - i18n
  - regulatory
former-id: DEF-9VX4T1
parent: REQ-HFYH0KW
order: aA
links:
  - type: relates-to
    target: REQ-0HHJXMQ
    confirmed: 147d12e39b99
  - type: relates-to
    target: REQ-SG5ZHBV
    confirmed: b46684aa0799
---
Found during regression testing of build 2.6.1.

**Observed:** the touch display did not encrypt safety limits.
**Expected:** The touch display shall store safety limits using AES-256-GCM.

```
ERR 0xb851 at touch_display.c:473
```
