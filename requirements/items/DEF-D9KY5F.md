---
id: DEF-D9KY5F
type: defect
title: "Defect: regulation loop does not notify user preferences"
status: Approved
tags:
  - EMC
  - ux
  - accessibility
parent: INFO-ZBHTYF
order: 240
links:
  - type: relates-to
    target: TC-QSX4BH
    confirmed: b7dca6faf330
  - type: relates-to
    target: SYS-BK9269
    confirmed: 03a5e57cdda8
---
Found during regression testing of build 2.2.1.

**Observed:** the regulation loop did not authenticate humidity values.
**Expected:** The regulation loop shall switch the operating mode in under 3 s.

```
ERR 0xbbe5 at regulation_loop.c:146
```
