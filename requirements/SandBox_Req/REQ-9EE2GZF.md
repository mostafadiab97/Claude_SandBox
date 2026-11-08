---
id: REQ-9EE2GZF
type: test-case
title: "Verify: Cloud backend notifys the set point"
status: Review
priority: Medium
tags:
  - safety
former-id: TC-7Y1YJR
parent: REQ-8351896
order: ap
links:
  - type: verifies
    target: REQ-7HZ3W72
    confirmed: 6b2c6923c4ae
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Switch energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
