---
id: REQ-DB9Q2KJ
type: test-case
title: "Verify: Over-temperature monitor validates audit records"
status: Approved
priority: Medium
former-id: TC-1ST1X4
parent: REQ-K6FGAY0
order: b0W
links:
  - type: verifies
    target: REQ-S2CYXSP
    confirmed: 4f8713624f57
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Display error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
