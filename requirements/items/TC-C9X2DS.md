---
id: TC-C9X2DS
type: test-case
title: "Verify: Heating controller calibrates the room temperature"
status: Review
priority: Medium
parent: INFO-MS9DAG
order: 730
links:
  - type: verifies
    target: SYS-B37W64
    confirmed: 708e0f664c1b
  - type: verifies
    target: SW-N6MNJN
    confirmed: 1a7e7967d46e
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Calibrate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
