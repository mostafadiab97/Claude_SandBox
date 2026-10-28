---
id: TC-87Z4K0
type: test-case
title: "Regression: Local API stores user preferences"
status: Review
priority: Medium
owner: M. Farouk
parent: INFO-ECHASH
order: 2010
links:
  - type: verifies
    target: SYS-RF310F
    confirmed: bc4cb8d2d781
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Authenticate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
