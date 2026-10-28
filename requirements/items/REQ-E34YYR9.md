---
id: REQ-E34YYR9
type: test-case
title: "Regression: Home dashboard synchronises schedule entries"
status: Review
priority: High
owner: N. Kamal
tags:
  - customer-request
  - accessibility
former-id: TC-CMHNKQ
parent: REQ-6H15AV2
order: b2B
links:
  - type: verifies
    target: REQ-JYSBE1D
    confirmed: 6e1a778017fa
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Authenticate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
