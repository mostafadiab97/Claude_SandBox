---
id: DEF-9VX4T1
type: defect
title: "Defect: touch display does not restore energy consumption"
status: Approved
priority: Medium
owner: S. Adel
tags:
  - ux
  - i18n
  - regulatory
parent: INFO-7HY7F9
order: 110
links:
  - type: relates-to
    target: TC-TQ0KN5
  - type: relates-to
    target: SYS-EFJFCR
---
Found during regression testing of build 2.6.1.

**Observed:** the touch display did not encrypt safety limits.
**Expected:** The touch display shall store safety limits using AES-256-GCM.

```
ERR 0xb851 at touch_display.c:473
```
