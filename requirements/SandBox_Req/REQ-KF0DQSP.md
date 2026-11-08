---
id: REQ-KF0DQSP
type: test-case
title: "Verify: Heating controller stores the set point"
status: Draft
priority: High
owner: H. Mostafa
former-id: TC-TDBPB8
parent: REQ-XGWSK2K
order: b12
links:
  - type: verifies
    target: REQ-16HDKES
    confirmed: b4b17cd08794
  - type: verifies
    target: REQ-V85XV1M
    confirmed: 05dae165bad7
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Restore audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
