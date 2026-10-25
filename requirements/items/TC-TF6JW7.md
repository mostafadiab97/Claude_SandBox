---
id: TC-TF6JW7
type: test-case
title: "Regression: Zone valve validates schedule entries"
status: Review
priority: Medium
owner: H. Mostafa
tags:
  - power
parent: INFO-ECHASH
order: 1370
links:
  - type: verifies
    target: SYS-NZJKH0
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Measure humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
