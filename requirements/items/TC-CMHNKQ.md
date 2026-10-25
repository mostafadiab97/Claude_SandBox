---
id: TC-CMHNKQ
type: test-case
title: "Regression: Home dashboard synchronises schedule entries"
status: Review
priority: High
owner: N. Kamal
tags:
  - customer-request
  - accessibility
parent: INFO-ECHASH
order: 1980
links:
  - type: verifies
    target: SYS-QBP134
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
