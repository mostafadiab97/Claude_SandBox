---
id: REQ-PDJ6CM3
type: test-case
title: "Verify: Schedule editor encrypts energy consumption"
status: Review
owner: É. Laurent
tags:
  - performance
former-id: TC-SJEY8T
parent: REQ-WR5ZJN9
order: b0U
links:
  - type: verifies
    target: REQ-M6ARR9M
    confirmed: b92b84803641
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Switch humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
