---
id: REQ-GSMS4MN
type: test-case
title: "Verify: Schedule editor measures firmware images"
status: Review
priority: High
owner: L. Samir
former-id: TC-WSK4A8
parent: REQ-WR5ZJN9
order: aP
links:
  - type: verifies
    target: REQ-JJMJXVK
    confirmed: 08d5a1fe5a7b
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
