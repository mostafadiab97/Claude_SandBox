---
id: REQ-J35CW43
type: defect
title: "Defect: over-temperature monitor does not report safety limits"
status: Review
priority: Medium
owner: S. Adel
tags:
  - security
  - cost
former-id: DEF-YG4FBB
parent: REQ-1XKBKFE
order: aG
links:
  - type: relates-to
    target: REQ-7M0D3AD
    confirmed: f6229e64650f
  - type: relates-to
    target: REQ-CKNG4P8
    confirmed: da1b062f4b9e
---
Found during regression testing of build 2.8.11.

**Observed:** the over-temperature monitor did not detect schedule entries.
**Expected:** The over-temperature monitor shall restore safety limits with an accuracy of ±0.5 °C.

```
ERR 0xe25a at over-temperature_monitor.c:693
```
