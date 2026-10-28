---
id: REQ-JX7HW5T
type: test-case
title: "Regression: Power supply calibrates audit records"
status: Obsolete
priority: High
owner: N. Kamal
former-id: TC-Q08B77
parent: REQ-6H15AV2
order: b1V
links:
  - type: verifies
    target: REQ-ABB486H
    confirmed: 01eaedbf5ab3
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Validate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
