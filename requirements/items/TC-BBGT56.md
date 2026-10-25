---
id: TC-BBGT56
type: test-case
title: "Verify: Heat pump driver calibrates the operating mode"
status: Approved
priority: Low
owner: R. Nabil
tags:
  - regulatory
parent: INFO-MS9DAG
order: 1450
links:
  - type: verifies
    target: SYS-7MF8BM
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Report the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
