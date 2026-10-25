---
id: TC-23EW3J
type: test-case
title: "Verify: Regulation loop encrypts the room temperature"
status: Approved
priority: Low
owner: A. Hassan
parent: INFO-MS9DAG
order: 1260
links:
  - type: verifies
    target: SYS-8F73DW
  - type: verifies
    target: SW-Q509HV
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Switch the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
