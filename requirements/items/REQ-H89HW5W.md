---
id: REQ-H89HW5W
type: test-case
title: "Verify: Heating controller calibrates the room temperature"
status: Review
priority: Medium
former-id: TC-C9X2DS
parent: REQ-XGWSK2K
order: b0A
links:
  - type: verifies
    target: REQ-FEE2S5J
    confirmed: 708e0f664c1b
  - type: verifies
    target: REQ-YYZQMQ6
    confirmed: 1a7e7967d46e
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Calibrate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
