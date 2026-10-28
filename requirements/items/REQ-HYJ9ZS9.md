---
id: REQ-HYJ9ZS9
type: test-case
title: "Regression: Login screen encrypts error conditions"
status: Draft
priority: Medium
owner: É. Laurent
former-id: TC-E8TY9H
parent: REQ-6H15AV2
order: b10
links:
  - type: verifies
    target: REQ-CCRB185
    confirmed: 4c561d45744d
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Display humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
