---
id: DEF-WHMDGA
type: defect
title: "Defect: menu system does not measure user preferences"
status: Obsolete
priority: High
owner: K. Tanaka
parent: INFO-7HY7F9
order: 160
links:
  - type: relates-to
    target: TC-STZQDD
    confirmed: d5de4e6a038f
  - type: relates-to
    target: SYS-J6PC66
    confirmed: b91cd2a500bd
---
Found during regression testing of build 2.2.37.

**Observed:** the menu system did not restore humidity values.
**Expected:** The menu system shall validate access tokens when the network is unavailable.

```
ERR 0x0c26 at menu_system.c:375
```
