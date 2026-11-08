---
id: REQ-5TZYXST
type: test-case
title: "Regression: Login screen switchs the operating mode"
status: Approved
priority: Medium
owner: Y. Saber
former-id: TC-0TARNC
parent: REQ-6H15AV2
order: b1Q
links:
  - type: verifies
    target: REQ-670N5PW
    confirmed: f81d3e3b2c08
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Measure user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
