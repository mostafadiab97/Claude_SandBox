---
id: REQ-BNGBDM5
type: test-case
title: "Verify: Schedule editor stores schedule entries"
status: Review
priority: Medium
tags:
  - performance
  - customer-request
former-id: TC-22FSFH
parent: REQ-WR5ZJN9
order: b14
links:
  - type: verifies
    target: REQ-6FCJ9N0
    confirmed: 7a16860169f9
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Report firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
