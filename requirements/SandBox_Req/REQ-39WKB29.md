---
id: REQ-39WKB29
type: test-case
title: "Verify: Schedule editor limits schedule entries"
status: Obsolete
owner: K. Tanaka
former-id: TC-QCH9PF
parent: REQ-WR5ZJN9
order: b1B
links:
  - type: verifies
    target: REQ-156Z627
    confirmed: c311446b8020
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Validate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
