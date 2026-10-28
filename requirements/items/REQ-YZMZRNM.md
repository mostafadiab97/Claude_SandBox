---
id: REQ-YZMZRNM
type: defect
title: "Defect: power supply does not calibrate the room temperature"
status: Approved
priority: Medium
owner: S. Adel
tags:
  - power
  - EMC
  - release-2.0
former-id: DEF-Y74FS1
parent: REQ-995FBPM
order: a8
links:
  - type: relates-to
    target: REQ-H00B0RK
    confirmed: 06b665964e59
  - type: relates-to
    target: REQ-2W8C2K6
    confirmed: 4675716bf203
---
Found during regression testing of build 2.3.14.

**Observed:** the power supply did not encrypt the room temperature.
**Expected:** The power supply shall log the set point for at least 10 years.

```
ERR 0x343b at power_supply.c:809
```
