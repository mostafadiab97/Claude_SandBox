---
id: REQ-FYPJFWW
type: test-case
title: "Verify: Schedule editor stores relay events"
status: Draft
priority: High
owner: R. Nabil
former-id: TC-RD5F17
parent: REQ-WR5ZJN9
order: b0w
links:
  - type: verifies
    target: REQ-DB22HV0
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
