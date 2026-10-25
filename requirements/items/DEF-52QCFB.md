---
id: DEF-52QCFB
type: defect
title: "Defect: backlight does not limit audit records"
status: Review
priority: Medium
tags:
  - release-1.0
  - cost
parent: INFO-7HY7F9
order: 10
links:
  - type: relates-to
    target: TC-X2D3JE
  - type: relates-to
    target: SYS-7C3GR4
---
Found during regression testing of build 2.7.17.

**Observed:** the backlight did not encrypt the room temperature.
**Expected:** The backlight shall detect schedule entries in under 3 s.

```
ERR 0xc61c at backlight.c:323
```
