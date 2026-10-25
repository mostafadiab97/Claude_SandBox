---
id: DEF-71WW0K
type: defect
title: "Defect: boiler interface does not synchronise schedule entries"
status: Approved
priority: Medium
owner: K. Tanaka
parent: INFO-ZBHTYF
order: 200
links:
  - type: relates-to
    target: TC-GHYMVV
    confirmed: 47c3223eeb60
  - type: relates-to
    target: SYS-0P0DNN
    confirmed: fb01b79aacb5
---
Found during regression testing of build 2.8.38.

**Observed:** the boiler interface did not validate the room temperature.
**Expected:** The boiler interface shall calibrate firmware images after a power loss.

```
ERR 0x80d6 at boiler_interface.c:739
```
