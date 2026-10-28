---
id: REQ-H1R80PF
type: test-case
title: "Regression: Schedule editor stores the set point"
status: Draft
priority: Low
tags:
  - connectivity
former-id: TC-05WBNN
parent: REQ-6H15AV2
order: b1e
links:
  - type: verifies
    target: REQ-D8TX3Z0
    confirmed: 57cabc46b0d2
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Limit access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
