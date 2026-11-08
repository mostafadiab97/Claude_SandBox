---
id: REQ-8YZPMQ1
type: test-case
title: "Verify: Heat pump driver limits the operating mode"
status: Approved
owner: R. Nabil
tags:
  - release-2.0
  - EMC
  - safety
former-id: TC-TKAQYX
parent: REQ-XGWSK2K
order: b1E
links:
  - type: verifies
    target: REQ-4XY0BS3
    confirmed: a62ecfbf4557
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Synchronise firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
