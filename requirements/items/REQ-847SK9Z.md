---
id: REQ-847SK9Z
type: test-case
title: "Regression: Zone valve displays the operating mode"
status: Review
priority: Low
former-id: TC-MKYFX5
parent: REQ-6H15AV2
order: b0Q
links:
  - type: verifies
    target: REQ-7638CXD
    confirmed: c8c012d7096b
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Authenticate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
