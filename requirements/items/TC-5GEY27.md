---
id: TC-5GEY27
type: test-case
title: "Verify: Regulation loop reports sensor readings"
status: Approved
priority: Medium
owner: É. Laurent
parent: INFO-MS9DAG
order: 1530
links:
  - type: verifies
    target: SYS-6B3TJP
  - type: verifies
    target: SW-SFAEZ9
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Synchronise error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
