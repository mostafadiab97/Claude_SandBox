---
id: REQ-T65G4HD
type: defect
title: "Defect: backlight does not limit audit records"
status: Review
priority: Medium
tags:
  - release-1.0
  - cost
former-id: DEF-52QCFB
parent: REQ-HFYH0KW
order: a0
links:
  - type: relates-to
    target: REQ-BA58DRF
    confirmed: 8852a015faf8
  - type: relates-to
    target: REQ-TEEHWEZ
    confirmed: d6385afd3348
---
Found during regression testing of build 2.7.17.

**Observed:** the backlight did not encrypt the room temperature.
**Expected:** The backlight shall detect schedule entries in under 3 s.

```
ERR 0xc61c at backlight.c:323
```
