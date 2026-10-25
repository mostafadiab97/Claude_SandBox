---
id: TC-TQV45N
type: test-case
title: "Verify: Over-temperature monitor measures sensor readings"
status: Approved
priority: Medium
owner: É. Laurent
parent: INFO-Z4TW4B
order: 290
links:
  - type: verifies
    target: SYS-WNE3D0
  - type: verifies
    target: SW-89WYP8
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Limit schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
