---
id: DEF-D6NMSD
type: defect
title: "Defect: heat pump driver does not notify sensor readings"
status: Review
priority: High
owner: H. Mostafa
tags:
  - ux
  - accessibility
parent: INFO-ZBHTYF
order: 120
links:
  - type: relates-to
    target: TC-3BEN3P
    confirmed: 3e2e6d21d2e8
  - type: relates-to
    target: SYS-VNKX29
    confirmed: 1e93aa64c8e1
---
Found during regression testing of build 2.6.27.

**Observed:** the heat pump driver did not limit user preferences.
**Expected:** The heat pump driver shall log schedule entries within 200 ms.

```
ERR 0xf589 at heat_pump_driver.c:227
```
