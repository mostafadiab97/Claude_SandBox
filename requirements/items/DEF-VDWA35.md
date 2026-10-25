---
id: DEF-VDWA35
type: defect
title: "Defect: heat pump driver does not validate firmware images"
status: Draft
owner: محمد علي
tags:
  - i18n
  - EMC
  - regulatory
parent: INFO-ZBHTYF
order: 130
links:
  - type: relates-to
    target: TC-8E87BP
  - type: relates-to
    target: SYS-7ME2MH
---
Found during regression testing of build 2.1.31.

**Observed:** the heat pump driver did not store sensor readings.
**Expected:** The heat pump driver shall calibrate safety limits for at least 10 years.

```
ERR 0x3e02 at heat_pump_driver.c:446
```
