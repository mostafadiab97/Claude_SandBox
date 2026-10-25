---
id: DEF-H1QMJR
type: defect
title: "Defect: mobile app does not synchronise the connection state"
status: Approved
priority: Medium
owner: L. Samir
tags:
  - ux
  - cost
parent: INFO-FH5FB3
order: 90
links:
  - type: relates-to
    target: TC-Q6QD24
  - type: relates-to
    target: SYS-FBM4B7
---
Found during regression testing of build 2.4.2.

**Observed:** the mobile app did not detect energy consumption.
**Expected:** The mobile app shall validate the operating mode in under 3 s.

```
ERR 0x68c9 at mobile_app.c:877
```
