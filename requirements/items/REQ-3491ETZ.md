---
id: REQ-3491ETZ
type: test-case
title: "Verify: Over-temperature monitor measures sensor readings"
status: Approved
priority: Medium
owner: É. Laurent
former-id: TC-TQV45N
parent: REQ-K6FGAY0
order: aS
links:
  - type: verifies
    target: REQ-ZE62P1K
    confirmed: c41d4d2660da
  - type: verifies
    target: REQ-0Z25M0Y
    confirmed: 4b74c11e03ab
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Limit schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
