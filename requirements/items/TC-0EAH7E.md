---
id: TC-0EAH7E
type: test-case
title: "Verify: Cloud backend synchronises error conditions"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - accessibility
  - cost
  - performance
parent: INFO-7P4D8D
order: 930
links:
  - type: verifies
    target: SYS-XWNGQ6
  - type: verifies
    target: SW-ZG8HVV
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Calibrate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
