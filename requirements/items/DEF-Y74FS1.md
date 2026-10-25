---
id: DEF-Y74FS1
type: defect
title: "Defect: power supply does not calibrate the room temperature"
status: Approved
priority: Medium
owner: S. Adel
tags:
  - power
  - EMC
  - release-2.0
parent: INFO-BB7M2N
order: 90
links:
  - type: relates-to
    target: TC-571QHG
  - type: relates-to
    target: SYS-C6GTWA
---
Found during regression testing of build 2.3.14.

**Observed:** the power supply did not encrypt the room temperature.
**Expected:** The power supply shall log the set point for at least 10 years.

```
ERR 0x343b at power_supply.c:809
```
