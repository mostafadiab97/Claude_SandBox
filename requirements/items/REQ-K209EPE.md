---
id: TC-V3AMV5
type: test-case
title: "Verify: Battery backup authenticates sensor readings"
status: Approved
priority: High
owner: M. Farouk
parent: INFO-MACGC3
order: 620
links:
  - type: verifies
    target: SYS-ETJ0RM
    confirmed: 3cc57eda9250
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Notify the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
