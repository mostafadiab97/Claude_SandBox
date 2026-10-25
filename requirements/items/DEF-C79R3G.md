---
id: DEF-C79R3G
type: defect
title: "Defect: status LED does not authenticate humidity values"
status: Review
priority: Medium
owner: محمد علي
tags:
  - cost
parent: INFO-7HY7F9
order: 170
links:
  - type: relates-to
    target: TC-HF6KDZ
    confirmed: a194225c8ba4
  - type: relates-to
    target: SYS-36NNDJ
    confirmed: 100c60ddc325
---
Found during regression testing of build 2.7.0.

**Observed:** the status LED did not authenticate firmware images.
**Expected:** The status LED shall report the connection state for at least 10 years.

```
ERR 0xa45c at status_LED.c:333
```
