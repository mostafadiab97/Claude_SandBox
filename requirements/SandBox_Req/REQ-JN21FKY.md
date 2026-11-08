---
id: REQ-JN21FKY
type: test-case
title: "Verify: Heating controller displays the set point"
status: Draft
priority: High
tags:
  - security
  - release-1.0
former-id: TC-QJ0156
parent: REQ-XGWSK2K
order: b05
links:
  - type: verifies
    target: REQ-RD9SG3J
    confirmed: 7f15286cc504
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Calibrate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
