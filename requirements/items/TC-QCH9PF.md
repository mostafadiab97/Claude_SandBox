---
id: TC-QCH9PF
type: test-case
title: "Verify: Schedule editor limits schedule entries"
status: Obsolete
owner: K. Tanaka
parent: INFO-J0FETE
order: 1360
links:
  - type: verifies
    target: SYS-HB2DW1
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
