---
id: REQ-4YD7X3W
type: test-case
title: "Verify: Heat pump driver authenticates humidity values"
status: Approved
priority: High
former-id: TC-A400G5
parent: REQ-XGWSK2K
order: b10
links:
  - type: verifies
    target: REQ-2SJ1GHM
    confirmed: 3d6bd0f5636f
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Limit audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
