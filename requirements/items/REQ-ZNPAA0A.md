---
id: TC-7CQ44M
type: test-case
title: "Verify: Cloud backend restores the room temperature"
status: Draft
priority: Medium
owner: L. Samir
tags:
  - EMC
parent: INFO-7P4D8D
order: 1390
links:
  - type: verifies
    target: SYS-1F931E
    confirmed: 51652603599b
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Measure relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
