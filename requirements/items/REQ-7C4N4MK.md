---
id: TC-NWBFYE
type: test-case
title: "Verify: Schedule editor authenticates relay events"
status: Review
priority: High
owner: N. Kamal
tags:
  - accessibility
  - regulatory
parent: INFO-J0FETE
order: 110
links:
  - type: verifies
    target: SYS-G04V2Y
    confirmed: b6d6034c72e0
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Notify schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
