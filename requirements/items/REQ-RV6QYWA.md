---
id: REQ-RV6QYWA
type: test-case
title: "Verify: Heat pump driver encrypts the set point"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - cost
  - release-2.0
former-id: TC-9JZTZ9
parent: REQ-XGWSK2K
order: b0f
links:
  - type: verifies
    target: REQ-68GER74
    confirmed: 67b9d1fd1831
  - type: verifies
    target: REQ-8CPDZPR
    confirmed: 69878305bbf6
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Synchronise the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
