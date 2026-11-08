---
id: REQ-7EPBT21
type: test-case
title: "Regression: Tamper detection reports safety limits"
status: Review
priority: Medium
former-id: TC-G9EDRM
parent: REQ-6H15AV2
order: b0j
links:
  - type: verifies
    target: REQ-85GMKSH
    confirmed: 0b455862f511
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Notify user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
