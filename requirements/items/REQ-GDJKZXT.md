---
id: DEF-YH0GV6
type: defect
title: "Defect: home dashboard does not synchronise energy consumption"
status: Draft
priority: High
owner: M. Farouk
tags:
  - ux
parent: INFO-FH5FB3
order: 50
links:
  - type: relates-to
    target: TC-GCB1K2
    confirmed: 3c04c4dcf75e
  - type: relates-to
    target: SYS-EB0Q7V
    confirmed: 7707b9c36b9c
---
Found during regression testing of build 2.2.13.

**Observed:** the home dashboard did not display the connection state.
**Expected:** The home dashboard shall validate firmware images in all supported languages.

```
ERR 0xbef0 at home_dashboard.c:679
```
