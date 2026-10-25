---
id: TC-TDBPB8
type: test-case
title: "Verify: Heating controller stores the set point"
status: Draft
priority: High
owner: H. Mostafa
parent: INFO-MS9DAG
order: 1270
links:
  - type: verifies
    target: SYS-745K9S
  - type: verifies
    target: SW-V4SAZB
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Restore audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
