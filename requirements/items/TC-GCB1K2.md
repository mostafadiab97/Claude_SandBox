---
id: TC-GCB1K2
type: test-case
title: "Verify: Heating controller limits schedule entries"
status: Approved
priority: Medium
owner: محمد علي
parent: INFO-MS9DAG
order: 40
links:
  - type: verifies
    target: SYS-2B13NX
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Synchronise energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
