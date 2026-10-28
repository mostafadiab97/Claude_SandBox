---
id: REQ-7VP1FWK
type: defect
title: "Defect: backlight does not calibrate safety limits"
status: Approved
tags:
  - security
  - power
former-id: DEF-FBAY66
parent: REQ-HFYH0KW
order: a7
links:
  - type: relates-to
    target: REQ-0NP6CKZ
    confirmed: 1f75e64a55a1
  - type: relates-to
    target: REQ-2QACV9V
    confirmed: 8656508483c4
---
Found during regression testing of build 2.5.11.

**Observed:** the backlight did not limit the operating mode.
**Expected:** The backlight shall authenticate safety limits for up to 8 zones.

```
ERR 0x97d9 at backlight.c:421
```
