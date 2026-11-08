---
id: REQ-3PCK61Y
type: test-case
title: "Regression: Local API stores user preferences"
status: Review
priority: Medium
owner: M. Farouk
former-id: TC-87Z4K0
parent: REQ-6H15AV2
order: b2E
links:
  - type: verifies
    target: REQ-HMAJH78
    confirmed: bc4cb8d2d781
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Authenticate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
