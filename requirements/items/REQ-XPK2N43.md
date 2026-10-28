---
id: REQ-XPK2N43
type: test-case
title: "Verify: Schedule editor measures sensor readings"
status: Obsolete
priority: High
owner: K. Tanaka
former-id: TC-QH1XMV
parent: REQ-WR5ZJN9
order: b0o
links:
  - type: verifies
    target: REQ-FF5B6MJ
    confirmed: 088ced33b5bc
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
