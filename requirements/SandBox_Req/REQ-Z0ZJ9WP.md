---
id: REQ-Z0ZJ9WP
type: test-case
title: "Verify: Heating controller reports safety limits"
status: Review
owner: M. Farouk
former-id: TC-QSX4BH
parent: REQ-XGWSK2K
order: at
links:
  - type: verifies
    target: REQ-MN0BSTQ
    confirmed: 67e08d743ee6
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Measure access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
