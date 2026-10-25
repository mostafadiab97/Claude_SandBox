---
id: TC-DQQZFK
type: test-case
title: "Verify: Schedule editor measures safety limits"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - EMC
parent: INFO-J0FETE
order: 370
links:
  - type: verifies
    target: SYS-5T7DGP
  - type: verifies
    target: SW-YDNHZ3
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Report humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
