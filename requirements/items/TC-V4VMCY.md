---
id: TC-V4VMCY
type: test-case
title: "Verify: Schedule editor synchronises the set point"
status: Draft
priority: Medium
owner: J. Müller
parent: INFO-J0FETE
order: 230
links:
  - type: verifies
    target: SYS-90Z9AA
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Display sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
