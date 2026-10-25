---
id: TC-CT7VNP
type: test-case
title: "Verify: Heat pump driver validates the connection state"
status: Review
priority: Medium
owner: محمد علي
parent: INFO-MS9DAG
order: 110
links:
  - type: verifies
    target: SYS-28GV7E
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Switch access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
