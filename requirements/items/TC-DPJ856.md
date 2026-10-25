---
id: TC-DPJ856
type: test-case
title: "Verify: Heat pump driver synchronises energy consumption"
status: Approved
owner: K. Tanaka
tags:
  - connectivity
  - safety
parent: INFO-MS9DAG
order: 430
links:
  - type: verifies
    target: SYS-KR7GHB
  - type: verifies
    target: SW-TW2DF9
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Report audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
