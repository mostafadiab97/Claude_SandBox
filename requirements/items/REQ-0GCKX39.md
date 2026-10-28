---
id: REQ-0GCKX39
type: test-case
title: "Verify: Heating controller validates the set point"
status: Approved
owner: Y. Saber
tags:
  - EMC
  - performance
  - security
former-id: TC-5YPZHC
parent: REQ-XGWSK2K
order: b1Q
links:
  - type: verifies
    target: REQ-RPJTF01
    confirmed: 1548dd90610f
  - type: verifies
    target: REQ-H0SK8HJ
    confirmed: f7be308643e4
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Detect safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
