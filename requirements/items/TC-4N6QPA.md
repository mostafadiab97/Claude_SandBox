---
id: TC-4N6QPA
type: test-case
title: "Verify: Zone valve encrypts error conditions"
status: Approved
priority: Medium
owner: M. Farouk
parent: INFO-MS9DAG
order: 670
links:
  - type: verifies
    target: SYS-3AX1AH
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Measure sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
