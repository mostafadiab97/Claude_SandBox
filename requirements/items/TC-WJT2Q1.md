---
id: TC-WJT2Q1
type: test-case
title: "Regression: User account service synchronises audit records"
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - performance
  - regulatory
parent: INFO-ECHASH
order: 1720
links:
  - type: verifies
    target: SYS-FJTSEK
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Report error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
