---
id: DEF-5EJ3P8
type: defect
title: "Defect: boiler interface does not synchronise user preferences"
status: Approved
priority: High
owner: محمد علي
tags:
  - release-1.0
parent: INFO-ZBHTYF
order: 160
links:
  - type: relates-to
    target: TC-CT7VNP
  - type: relates-to
    target: SYS-5EWC97
---
Found during regression testing of build 2.5.38.

**Observed:** the boiler interface did not calibrate sensor readings.
**Expected:** The boiler interface shall report the room temperature in under 3 s.

```
ERR 0xc21d at boiler_interface.c:736
```
