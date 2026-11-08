---
id: REQ-2WBS4GK
type: defect
title: "Defect: battery backup does not log access tokens"
status: Approved
owner: K. Tanaka
tags:
  - ux
  - safety
  - security
former-id: DEF-9MF12V
parent: REQ-995FBPM
order: aC
links:
  - type: relates-to
    target: REQ-G8WZ1D6
    confirmed: 3e2e6d21d2e8
  - type: relates-to
    target: REQ-JTATXJJ
    confirmed: 482dfc4da294
---
Found during regression testing of build 2.3.39.

**Observed:** the battery backup did not notify sensor readings.
**Expected:** The battery backup shall switch access tokens in under 3 s.

```
ERR 0x2f6f at battery_backup.c:809
```
