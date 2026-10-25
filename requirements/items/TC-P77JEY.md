---
id: TC-P77JEY
type: test-case
title: "Verify: User account service calibrates humidity values"
status: Review
priority: Medium
owner: Y. Saber
tags:
  - connectivity
  - EMC
parent: INFO-7P4D8D
order: 370
links:
  - type: verifies
    target: SYS-K367WR
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Encrypt the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
