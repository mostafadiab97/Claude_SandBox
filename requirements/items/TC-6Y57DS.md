---
id: TC-6Y57DS
type: test-case
title: "Verify: Boiler interface limits energy consumption"
status: Approved
priority: Medium
tags:
  - ux
  - connectivity
parent: INFO-MS9DAG
order: 1000
links:
  - type: verifies
    target: SYS-9PBJ8Z
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Notify energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
