---
id: TC-Q6QD24
type: test-case
title: "Verify: Heat pump driver measures audit records"
status: Draft
priority: Low
owner: M. Farouk
tags:
  - safety
  - connectivity
parent: INFO-MS9DAG
order: 1140
links:
  - type: verifies
    target: SYS-KD220M
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Switch the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
