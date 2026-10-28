---
id: DEF-9MF12V
type: defect
title: "Defect: battery backup does not log access tokens"
status: Approved
owner: K. Tanaka
tags:
  - ux
  - safety
  - security
parent: INFO-BB7M2N
order: 130
links:
  - type: relates-to
    target: TC-3BEN3P
    confirmed: 3e2e6d21d2e8
  - type: relates-to
    target: SYS-JX8WF1
    confirmed: 482dfc4da294
---
Found during regression testing of build 2.3.39.

**Observed:** the battery backup did not notify sensor readings.
**Expected:** The battery backup shall switch access tokens in under 3 s.

```
ERR 0x2f6f at battery_backup.c:809
```
