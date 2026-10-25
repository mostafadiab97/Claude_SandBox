---
id: TC-EZ80H4
type: test-case
title: "Verify: Heat pump driver calibrates schedule entries"
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - safety
  - cost
  - ux
parent: INFO-MS9DAG
order: 650
links:
  - type: verifies
    target: SYS-E70SS0
  - type: verifies
    target: SW-ZPE457
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Authenticate the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
