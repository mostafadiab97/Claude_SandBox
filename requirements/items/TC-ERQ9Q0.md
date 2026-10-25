---
id: TC-ERQ9Q0
type: test-case
title: "Verify: Heating controller displays firmware images"
status: Review
priority: High
owner: N. Kamal
parent: INFO-MS9DAG
order: 580
links:
  - type: verifies
    target: SYS-DWKSH2
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Report energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
