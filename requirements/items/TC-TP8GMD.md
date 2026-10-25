---
id: TC-TP8GMD
type: test-case
title: "Verify: Regulation loop calibrates the room temperature"
status: Approved
priority: High
parent: INFO-MS9DAG
order: 1120
links:
  - type: verifies
    target: SYS-M4QAQY
    confirmed: 4fabc5aa13e6
  - type: verifies
    target: SW-E0C6CJ
    confirmed: 54e0e57fc0f2
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Limit safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
