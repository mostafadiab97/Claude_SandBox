---
id: REQ-64EZ26N
type: test-case
title: "Verify: Over-temperature monitor validates energy consumption"
status: Approved
priority: Low
owner: S. Adel
former-id: TC-0RNA88
parent: REQ-K6FGAY0
order: aT
links:
  - type: verifies
    target: REQ-H6FDKCE
    confirmed: b81585ff6f2b
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Notify the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
