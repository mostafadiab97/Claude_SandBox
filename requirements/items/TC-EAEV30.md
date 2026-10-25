---
id: TC-EAEV30
type: test-case
title: "Regression: Heat pump driver reports sensor readings"
status: Draft
priority: Low
owner: É. Laurent
parent: INFO-ECHASH
order: 2050
links:
  - type: verifies
    target: SYS-S1BVE9
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Display the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
