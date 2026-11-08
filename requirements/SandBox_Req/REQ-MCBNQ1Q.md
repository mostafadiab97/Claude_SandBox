---
id: REQ-MCBNQ1Q
type: defect
title: "Defect: menu system does not store safety limits"
status: Approved
priority: High
owner: L. Samir
tags:
  - regulatory
  - performance
former-id: DEF-SBSKZ1
parent: REQ-HFYH0KW
order: a9
links:
  - type: relates-to
    target: REQ-K8QTJ1Q
    confirmed: 01121f023aa6
  - type: relates-to
    target: REQ-R9CA0V4
    confirmed: c0c5efe3652f
---
Found during regression testing of build 2.7.16.

**Observed:** the menu system did not notify relay events.
**Expected:** The menu system shall limit access tokens after a power loss.

```
ERR 0x6a03 at menu_system.c:483
```
