---
id: TC-Y0JR5E
type: test-case
title: "Verify: Relay board encrypts the set point"
status: Draft
priority: Medium
owner: محمد علي
parent: INFO-MACGC3
order: 1320
links:
  - type: verifies
    target: SYS-J3QEM9
  - type: verifies
    target: SW-BYVAYF
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Limit energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
