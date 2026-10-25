---
id: TC-KCW5P3
type: test-case
title: "Verify: OTA server synchronises error conditions"
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - cost
  - performance
parent: INFO-7P4D8D
order: 210
links:
  - type: verifies
    target: SYS-NM7171
  - type: verifies
    target: SW-A58ZR3
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Synchronise the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
