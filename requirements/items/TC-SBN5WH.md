---
id: TC-SBN5WH
type: test-case
title: "Verify: Heat pump driver synchronises safety limits"
status: Approved
owner: J. Müller
tags:
  - release-1.0
parent: INFO-MS9DAG
order: 950
links:
  - type: verifies
    target: SYS-ZRJGC6
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Detect energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
