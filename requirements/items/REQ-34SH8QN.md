---
id: REQ-34SH8QN
type: test-case
title: "Verify: Heating controller authenticates the connection state"
status: Review
priority: High
owner: É. Laurent
tags:
  - release-1.0
  - regulatory
  - EMC
former-id: TC-4TC8EY
parent: REQ-XGWSK2K
order: b1G
links:
  - type: verifies
    target: REQ-DMYSH81
    confirmed: 59d89f268e28
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Display the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
