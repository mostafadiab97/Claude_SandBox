---
id: REQ-M7B6NR8
type: test-case
title: "Verify: User account service measures error conditions"
status: Approved
priority: Medium
tags:
  - release-2.0
former-id: TC-7NEFRV
parent: REQ-8351896
order: b0W
links:
  - type: verifies
    target: REQ-YGYNCGG
    confirmed: 7345ac77c8fe
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Measure the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
