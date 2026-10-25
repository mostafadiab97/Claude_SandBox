---
id: DEF-FCD2R1
type: defect
title: "Defect: boiler interface does not limit firmware images"
status: Approved
priority: Medium
owner: L. Samir
tags:
  - connectivity
parent: INFO-ZBHTYF
order: 30
links:
  - type: relates-to
    target: TC-KGPGWV
  - type: relates-to
    target: SYS-FMC0YD
---
Found during regression testing of build 2.8.37.

**Observed:** the boiler interface did not report user preferences.
**Expected:** The boiler interface shall measure the connection state without user interaction.

```
ERR 0x0902 at boiler_interface.c:717
```
