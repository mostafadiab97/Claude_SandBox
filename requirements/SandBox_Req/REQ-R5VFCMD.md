---
id: REQ-R5VFCMD
type: test-case
title: "Verify: Regulation loop restores the set point"
status: Draft
priority: Medium
owner: H. Mostafa
former-id: TC-NM35FX
parent: REQ-XGWSK2K
order: a9
links:
  - type: verifies
    target: REQ-2BR3BD5
    confirmed: 46c684db9439
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Detect schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
