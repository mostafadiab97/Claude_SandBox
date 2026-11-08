---
id: REQ-W1HKXCS
type: test-case
title: "Regression: Schedule editor measures safety limits"
status: Review
priority: Low
owner: M. Farouk
tags:
  - safety
former-id: TC-5AMCAR
parent: REQ-6H15AV2
order: b0Y
links:
  - type: verifies
    target: REQ-DG88HFJ
    confirmed: 65eb9c0bc016
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Notify energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
