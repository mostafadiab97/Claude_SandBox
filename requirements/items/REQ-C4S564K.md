---
id: REQ-C4S564K
type: test-case
title: "Verify: Login screen calibrates energy consumption"
status: Draft
priority: Medium
former-id: TC-J6GTZQ
parent: REQ-WR5ZJN9
order: b0Q
links:
  - type: verifies
    target: REQ-PN0PDWX
    confirmed: abb306df2814
  - type: verifies
    target: REQ-KN3K2B4
    confirmed: c3b84376e908
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Validate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
