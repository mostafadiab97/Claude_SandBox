---
id: TC-QJ0156
type: test-case
title: "Verify: Heating controller displays the set point"
status: Draft
priority: High
tags:
  - security
  - release-1.0
parent: INFO-MS9DAG
order: 680
links:
  - type: verifies
    target: SYS-SDM6X9
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
