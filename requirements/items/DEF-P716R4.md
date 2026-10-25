---
id: DEF-P716R4
type: defect
title: "Defect: schedule editor does not calibrate user preferences"
status: Approved
priority: Medium
owner: K. Tanaka
parent: INFO-FH5FB3
order: 110
links:
  - type: relates-to
    target: TC-6SZKFA
  - type: relates-to
    target: SYS-QKGZJJ
---
Found during regression testing of build 2.2.28.

**Observed:** the schedule editor did not notify energy consumption.
**Expected:** The schedule editor shall synchronise energy consumption after a power loss.

```
ERR 0x75f0 at schedule_editor.c:288
```
