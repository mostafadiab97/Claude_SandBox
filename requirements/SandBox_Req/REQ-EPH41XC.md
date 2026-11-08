---
id: REQ-EPH41XC
type: test-case
title: "Verify: Boiler interface validates error conditions"
status: Review
priority: High
tags:
  - security
  - connectivity
former-id: TC-1Q70E6
parent: REQ-XGWSK2K
order: b0k
links:
  - type: verifies
    target: REQ-GE3XCDD
    confirmed: b3506b846105
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Display the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
