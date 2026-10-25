---
id: TC-WSK4A8
type: test-case
title: "Verify: Schedule editor measures firmware images"
status: Review
priority: High
owner: L. Samir
parent: INFO-J0FETE
order: 260
links:
  - type: verifies
    target: SYS-R2FDWQ
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Synchronise energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
