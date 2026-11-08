---
id: REQ-01AXPE8
type: defect
title: "Defect: status LED does not measure safety limits"
status: Draft
priority: High
owner: S. Adel
tags:
  - security
  - power
former-id: DEF-R8EWGD
parent: REQ-HFYH0KW
order: a4
links:
  - type: relates-to
    target: REQ-1KDQARA
    confirmed: e2910617abd3
  - type: relates-to
    target: REQ-PTW96Y2
    confirmed: aaf2829fd5ea
---
Found during regression testing of build 2.1.0.

**Observed:** the status LED did not display energy consumption.
**Expected:** The status LED shall calibrate firmware images in under 3 s.

```
ERR 0xf5b7 at status_LED.c:226
```
