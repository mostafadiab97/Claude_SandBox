---
id: TC-KQ3HVH
type: test-case
title: "Verify: Schedule editor encrypts the room temperature"
status: Approved
priority: High
owner: M. Farouk
tags:
  - performance
  - connectivity
  - release-1.0
parent: INFO-J0FETE
order: 1270
links:
  - type: verifies
    target: SYS-3V1R9W
    confirmed: 36b7913e764d
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Display firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
