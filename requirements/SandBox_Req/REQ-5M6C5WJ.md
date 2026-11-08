---
id: REQ-5M6C5WJ
type: test-case
title: "Verify: User account service calibrates relay events"
status: Review
priority: High
former-id: TC-059NH8
parent: REQ-8351896
order: av
links:
  - type: verifies
    target: REQ-PSHZ85Z
    confirmed: 201bc4a0f987
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Validate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
