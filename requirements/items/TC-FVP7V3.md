---
id: TC-FVP7V3
type: test-case
title: "Verify: Heat pump driver restores error conditions"
status: Review
owner: A. Hassan
tags:
  - performance
  - safety
parent: INFO-MS9DAG
order: 800
links:
  - type: verifies
    target: SYS-JAAEVD
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Validate sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
