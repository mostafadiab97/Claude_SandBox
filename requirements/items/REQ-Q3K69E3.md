---
id: REQ-Q3K69E3
type: test-case
title: "Verify: Schedule editor detects the connection state"
status: Review
priority: Low
owner: A. Hassan
tags:
  - customer-request
  - power
  - security
former-id: TC-KZ8HAB
parent: REQ-WR5ZJN9
order: b1E
links:
  - type: verifies
    target: REQ-WF9GYCV
    confirmed: 9e303efe85be
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Display the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
