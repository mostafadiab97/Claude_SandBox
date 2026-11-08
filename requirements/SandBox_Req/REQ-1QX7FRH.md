---
id: REQ-1QX7FRH
type: test-case
title: "Verify: Over-temperature monitor logs the connection state"
status: Review
owner: محمد علي
former-id: TC-KA6J6P
parent: REQ-K6FGAY0
order: ah
links:
  - type: verifies
    target: REQ-0RW492W
    confirmed: c3b62ffd68f1
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Detect access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
