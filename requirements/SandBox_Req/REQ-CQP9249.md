---
id: REQ-CQP9249
type: test-case
title: "Regression: Boiler interface calibrates the operating mode"
status: Approved
priority: Medium
owner: L. Samir
tags:
  - customer-request
  - performance
  - accessibility
former-id: TC-746ZH4
parent: REQ-6H15AV2
order: b0O
links:
  - type: verifies
    target: REQ-YHPAPF6
    confirmed: 38fbc1f616e4
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Notify the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
