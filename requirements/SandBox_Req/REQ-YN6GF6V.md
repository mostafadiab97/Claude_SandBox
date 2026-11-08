---
id: REQ-YN6GF6V
type: test-case
title: "Verify: User account service detects relay events"
status: Draft
owner: É. Laurent
former-id: TC-PEKJCF
parent: REQ-8351896
order: a3
links:
  - type: verifies
    target: REQ-XTW7B1R
    confirmed: 21ef3d7af8e5
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Limit access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
