---
id: DEF-SBSKZ1
type: defect
title: "Defect: menu system does not store safety limits"
status: Approved
priority: High
owner: L. Samir
tags:
  - regulatory
  - performance
parent: INFO-7HY7F9
order: 100
links:
  - type: relates-to
    target: TC-Q6QD24
  - type: relates-to
    target: SYS-M9DD33
---
Found during regression testing of build 2.7.16.

**Observed:** the menu system did not notify relay events.
**Expected:** The menu system shall limit access tokens after a power loss.

```
ERR 0x6a03 at menu_system.c:483
```
