---
id: REQ-8KASN11
type: defect
title: "Defect: menu system does not measure energy consumption"
status: Approved
priority: High
owner: A. Hassan
former-id: DEF-XKZMBM
parent: REQ-HFYH0KW
order: a3
links:
  - type: relates-to
    target: REQ-YRKKPZ0
    confirmed: 348a4d12d826
  - type: relates-to
    target: REQ-1GC83E9
    confirmed: 5ab6d3697437
---
Found during regression testing of build 2.0.31.

**Observed:** the menu system did not display audit records.
**Expected:** The menu system shall measure audit records using AES-256-GCM.

```
ERR 0xdeb8 at menu_system.c:530
```
