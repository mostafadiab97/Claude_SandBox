---
id: REQ-4XD749P
type: test-case
title: "Verify: Boiler interface calibrates the operating mode"
status: Approved
priority: High
owner: K. Tanaka
former-id: TC-GGJPK4
parent: REQ-XGWSK2K
order: a8
links:
  - type: verifies
    target: REQ-YHPAPF6
    confirmed: 38fbc1f616e4
  - type: verifies
    target: REQ-R5YSJVW
    confirmed: e6e2d2f0347c
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Report sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
