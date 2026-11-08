---
id: REQ-HJ6V8KS
type: test-case
title: "Regression: Heat pump driver calibrates the operating mode"
status: Approved
priority: High
tags:
  - security
former-id: TC-M2Z4T6
parent: REQ-6H15AV2
order: b2M
links:
  - type: verifies
    target: REQ-EMA1R60
    confirmed: df19f5a8810f
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Authenticate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
