---
id: REQ-3AV8FFS
type: defect
title: "Defect: heat pump driver does not validate firmware images"
status: Draft
owner: محمد علي
tags:
  - i18n
  - EMC
  - regulatory
former-id: DEF-VDWA35
parent: REQ-XJDN42Y
order: aC
links:
  - type: relates-to
    target: REQ-BRZTX12
    confirmed: 8210f80f4b2e
  - type: relates-to
    target: REQ-3753MVK
    confirmed: 212fa2a7c66a
---
Found during regression testing of build 2.1.31.

**Observed:** the heat pump driver did not store sensor readings.
**Expected:** The heat pump driver shall calibrate safety limits for at least 10 years.

```
ERR 0x3e02 at heat_pump_driver.c:446
```
