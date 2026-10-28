---
id: DEF-BB1NY2
type: defect
title: "Defect: status LED does not measure the room temperature"
status: Approved
priority: Medium
owner: محمد علي
parent: INFO-7HY7F9
order: 210
links:
  - type: relates-to
    target: TC-0WHVXH
    confirmed: 066f328ba2c5
  - type: relates-to
    target: SYS-378XSW
    confirmed: 5031ebc6a924
---
Found during regression testing of build 2.6.7.

**Observed:** the status LED did not display humidity values.
**Expected:** The status LED shall encrypt user preferences below 0.5 W in standby.

```
ERR 0xc978 at status_LED.c:619
```
