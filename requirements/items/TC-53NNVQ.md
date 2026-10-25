---
id: TC-53NNVQ
type: test-case
title: "Verify: Heat pump driver measures the connection state"
status: Review
priority: High
owner: É. Laurent
parent: INFO-MS9DAG
order: 1170
links:
  - type: verifies
    target: SYS-0DYZ84
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Detect energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
