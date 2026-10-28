---
id: TC-T1ZW3T
type: test-case
title: "Verify: Cloud backend validates schedule entries"
status: Approved
priority: Medium
tags:
  - connectivity
parent: INFO-7P4D8D
order: 220
links:
  - type: verifies
    target: SYS-KT3GD2
    confirmed: 8a0b2b4def8d
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Synchronise the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
