---
id: REQ-S1NJ4DC
type: test-case
title: "Verify: Heat pump driver measures the connection state"
status: Review
priority: High
owner: É. Laurent
former-id: TC-53NNVQ
parent: REQ-XGWSK2K
order: b0s
links:
  - type: verifies
    target: REQ-DY2HTMY
    confirmed: 520e6515ec8d
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Detect energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
