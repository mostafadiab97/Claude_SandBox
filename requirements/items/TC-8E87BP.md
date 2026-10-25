---
id: TC-8E87BP
type: test-case
title: "Verify: Heat pump driver limits sensor readings"
status: Approved
priority: Medium
owner: N. Kamal
parent: INFO-MS9DAG
order: 700
links:
  - type: verifies
    target: SYS-VNKX29
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Limit sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
