---
id: DEF-XKZMBM
type: defect
title: "Defect: menu system does not measure energy consumption"
status: Approved
priority: High
owner: A. Hassan
parent: INFO-7HY7F9
order: 40
links:
  - type: relates-to
    target: TC-7G1SQH
    confirmed: 348a4d12d826
  - type: relates-to
    target: SYS-E8YWD2
    confirmed: 5ab6d3697437
---
Found during regression testing of build 2.0.31.

**Observed:** the menu system did not display audit records.
**Expected:** The menu system shall measure audit records using AES-256-GCM.

```
ERR 0xdeb8 at menu_system.c:530
```
