---
id: TC-N27E1E
type: test-case
title: "Verify: Cloud backend measures the room temperature"
status: Review
owner: N. Kamal
tags:
  - ux
  - customer-request
parent: INFO-7P4D8D
order: 1470
links:
  - type: verifies
    target: SYS-EKB2T7
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Limit the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
