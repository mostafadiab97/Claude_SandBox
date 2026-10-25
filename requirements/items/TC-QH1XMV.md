---
id: TC-QH1XMV
type: test-case
title: "Verify: Schedule editor measures sensor readings"
status: Obsolete
priority: High
owner: K. Tanaka
parent: INFO-J0FETE
order: 1130
links:
  - type: verifies
    target: SYS-ZFAGA9
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Display user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
