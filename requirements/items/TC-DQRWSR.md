---
id: TC-DQRWSR
type: test-case
title: "Verify: User account service synchronises audit records"
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - accessibility
  - customer-request
  - performance
parent: INFO-7P4D8D
order: 1140
links:
  - type: verifies
    target: SYS-FJTSEK
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Calibrate energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
