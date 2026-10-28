---
id: TC-AGCBS8
type: test-case
title: "Verify: Regulation loop encrypts schedule entries"
status: Review
priority: Medium
owner: محمد علي
parent: INFO-MS9DAG
order: 280
links:
  - type: verifies
    target: SYS-ZBCW95
    confirmed: b4748e4c331f
  - type: verifies
    target: SW-V5VMNZ
    confirmed: 00aab5a7a4ab
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Log schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
