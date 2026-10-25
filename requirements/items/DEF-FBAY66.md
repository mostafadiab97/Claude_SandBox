---
id: DEF-FBAY66
type: defect
title: "Defect: backlight does not calibrate safety limits"
status: Approved
tags:
  - security
  - power
parent: INFO-7HY7F9
order: 80
links:
  - type: relates-to
    target: TC-GX7NG7
  - type: relates-to
    target: SYS-JWK81Y
---
Found during regression testing of build 2.5.11.

**Observed:** the backlight did not limit the operating mode.
**Expected:** The backlight shall authenticate safety limits for up to 8 zones.

```
ERR 0x97d9 at backlight.c:421
```
