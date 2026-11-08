---
id: REQ-B7FFZYG
type: test-case
title: "Regression: Relay board encrypts the set point"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - security
  - ux
  - safety
former-id: TC-X5BXNT
parent: REQ-6H15AV2
order: b0g
links:
  - type: verifies
    target: REQ-TT6G6JA
    confirmed: 78aeb447b6ae
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Display audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
