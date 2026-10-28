---
id: REQ-9S7J0H7
type: test-case
title: "Verify: Schedule editor stores audit records"
status: Approved
priority: Medium
owner: É. Laurent
former-id: TC-V92BGY
parent: REQ-WR5ZJN9
order: a1
links:
  - type: verifies
    target: REQ-XZGCQC0
    confirmed: 076f07709938
  - type: verifies
    target: REQ-FR4F14S
    confirmed: 00bc06cc95d8
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Restore schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
