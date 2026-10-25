---
id: TC-2RVGJE
type: test-case
title: "Verify: Schedule editor measures energy consumption"
status: Draft
priority: Medium
owner: Y. Saber
tags:
  - regulatory
  - release-2.0
parent: INFO-J0FETE
order: 1200
links:
  - type: verifies
    target: SYS-BKCGFY
  - type: verifies
    target: SW-81JA41
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Store user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
