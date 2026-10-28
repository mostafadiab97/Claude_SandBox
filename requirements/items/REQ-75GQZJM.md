---
id: REQ-75GQZJM
type: test-case
title: "Verify: User account service synchronises the operating mode"
status: Draft
priority: High
owner: N. Kamal
tags:
  - customer-request
  - performance
former-id: TC-FWX8C8
parent: REQ-8351896
order: b0f
links:
  - type: verifies
    target: REQ-J23W5Z5
    confirmed: 2a9e2d07c950
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Measure audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
