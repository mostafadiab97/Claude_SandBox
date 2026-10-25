---
id: TC-QSX4BH
type: test-case
title: "Verify: Heating controller reports safety limits"
status: Review
owner: M. Farouk
parent: INFO-MS9DAG
order: 560
links:
  - type: verifies
    target: SYS-HZRAQ2
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Measure access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
