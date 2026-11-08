---
id: REQ-GAQXP49
type: test-case
title: "Regression: Relay board reports schedule entries"
status: Review
owner: H. Mostafa
tags:
  - EMC
former-id: TC-EG5M1N
parent: REQ-6H15AV2
order: b1x
links:
  - type: verifies
    target: REQ-4QP6QW0
    confirmed: 79a5d5b3bb44
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Report energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
