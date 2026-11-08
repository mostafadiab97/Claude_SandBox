---
id: REQ-FRJXDG3
type: test-case
title: "Verify: Schedule editor measures relay events"
status: Draft
priority: Medium
former-id: TC-AQNVHZ
parent: REQ-WR5ZJN9
order: b0X
links:
  - type: verifies
    target: REQ-R3BD293
    confirmed: f3e0173269c9
  - type: verifies
    target: REQ-HAEYHZ6
    confirmed: e6cdf4908071
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Limit safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
