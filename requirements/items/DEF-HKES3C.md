---
id: DEF-HKES3C
type: defect
title: "Defect: status LED does not calibrate the connection state"
status: Draft
owner: M. Farouk
tags:
  - performance
  - ux
parent: INFO-7HY7F9
order: 140
links:
  - type: relates-to
    target: TC-QGG4X6
  - type: relates-to
    target: SYS-D5BE23
---
Found during regression testing of build 2.3.26.

**Observed:** the status LED did not store relay events.
**Expected:** The status LED shall encrypt the room temperature at least once per minute.

```
ERR 0x2e8e at status_LED.c:868
```
