---
id: TC-C9G5AT
type: test-case
title: "Verify: Boiler interface validates schedule entries"
status: Review
priority: Medium
owner: L. Samir
parent: INFO-MS9DAG
order: 1130
links:
  - type: verifies
    target: SYS-S4CRQY
  - type: verifies
    target: SW-GEQD7V
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Log sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
