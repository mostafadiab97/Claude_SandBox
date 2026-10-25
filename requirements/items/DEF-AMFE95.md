---
id: DEF-AMFE95
type: defect
title: "Defect: main PCB does not validate energy consumption"
status: Approved
priority: Medium
owner: S. Adel
parent: INFO-BB7M2N
order: 110
links:
  - type: relates-to
    target: TC-XVZ3TE
  - type: relates-to
    target: SYS-SZFE37
---
Found during regression testing of build 2.6.25.

**Observed:** the main PCB did not calibrate humidity values.
**Expected:** The main PCB shall synchronise relay events after a power loss.

```
ERR 0x374b at main_PCB.c:423
```
