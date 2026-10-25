---
id: DEF-R8EWGD
type: defect
title: "Defect: status LED does not measure safety limits"
status: Draft
priority: High
owner: S. Adel
tags:
  - security
  - power
parent: INFO-7HY7F9
order: 50
links:
  - type: relates-to
    target: TC-FY5MVC
    confirmed: e2910617abd3
  - type: relates-to
    target: SYS-1BYGW7
    confirmed: aaf2829fd5ea
---
Found during regression testing of build 2.1.0.

**Observed:** the status LED did not display energy consumption.
**Expected:** The status LED shall calibrate firmware images in under 3 s.

```
ERR 0xf5b7 at status_LED.c:226
```
