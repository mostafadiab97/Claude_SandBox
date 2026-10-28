---
id: TC-RD5F17
type: test-case
title: "Verify: Schedule editor stores relay events"
status: Draft
priority: High
owner: R. Nabil
parent: INFO-J0FETE
order: 1210
links:
  - type: verifies
    target: SYS-4B136B
    confirmed: f1cf885c4dcd
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Validate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
