---
id: TC-7BCZF6
type: test-case
title: "Verify: Tamper detection measures safety limits"
status: Draft
priority: Medium
owner: K. Tanaka
tags:
  - release-2.0
  - release-1.0
parent: INFO-Z4TW4B
order: 560
links:
  - type: verifies
    target: SYS-MGCE70
  - type: verifies
    target: SW-59VNQ4
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Display safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
