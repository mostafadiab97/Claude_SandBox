---
id: DEF-YG4FBB
type: defect
title: "Defect: over-temperature monitor does not report safety limits"
status: Review
priority: Medium
owner: S. Adel
tags:
  - security
  - cost
parent: INFO-6QFMYN
order: 170
links:
  - type: relates-to
    target: TC-VAJSZT
    confirmed: f6229e64650f
  - type: relates-to
    target: SYS-8FZWQN
    confirmed: da1b062f4b9e
---
Found during regression testing of build 2.8.11.

**Observed:** the over-temperature monitor did not detect schedule entries.
**Expected:** The over-temperature monitor shall restore safety limits with an accuracy of ±0.5 °C.

```
ERR 0xe25a at over-temperature_monitor.c:693
```
