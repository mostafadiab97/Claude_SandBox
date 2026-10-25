---
id: TC-MNWNAV
type: test-case
title: "Verify: Heating controller calibrates the room temperature"
status: Draft
priority: Medium
owner: A. Hassan
parent: INFO-MS9DAG
order: 1520
links:
  - type: verifies
    target: SYS-7JZD7P
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Restore the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
