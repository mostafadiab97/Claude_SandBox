---
id: TC-GHYMVV
type: test-case
title: "Verify: Boiler interface stores audit records"
status: Approved
tags:
  - customer-request
parent: INFO-MS9DAG
order: 490
links:
  - type: verifies
    target: SYS-B37VY2
  - type: verifies
    target: SW-R9FW76
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Measure the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
