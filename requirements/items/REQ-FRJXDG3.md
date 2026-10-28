---
id: TC-AQNVHZ
type: test-case
title: "Verify: Schedule editor measures relay events"
status: Draft
priority: Medium
parent: INFO-J0FETE
order: 960
links:
  - type: verifies
    target: SYS-9AYNBP
    confirmed: f3e0173269c9
  - type: verifies
    target: SW-AJP6HH
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
