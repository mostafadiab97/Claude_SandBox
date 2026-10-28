---
id: REQ-H7QHPM2
type: test-case
title: "Verify: Pairing process synchronises error conditions"
status: Approved
priority: Medium
owner: H. Mostafa
former-id: TC-517VPV
parent: REQ-67RQXCK
order: b12
links:
  - type: verifies
    target: REQ-GTJ8085
    confirmed: 62af45041e6e
  - type: verifies
    target: REQ-YC77EVS
    confirmed: 7e4eee25d689
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Measure energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
