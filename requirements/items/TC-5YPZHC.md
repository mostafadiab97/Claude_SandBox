---
id: TC-5YPZHC
type: test-case
title: "Verify: Heating controller validates the set point"
status: Approved
owner: Y. Saber
tags:
  - EMC
  - performance
  - security
parent: INFO-MS9DAG
order: 1510
links:
  - type: verifies
    target: SYS-9Y8YJ7
    confirmed: 1548dd90610f
  - type: verifies
    target: SW-CD64BA
    confirmed: f7be308643e4
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Detect safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
