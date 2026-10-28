---
id: TC-PFQKDN
type: test-case
title: "Verify: User account service validates firmware images"
status: Approved
priority: High
owner: K. Tanaka
tags:
  - security
parent: INFO-7P4D8D
order: 1280
links:
  - type: verifies
    target: SYS-Z3C3F8
    confirmed: 0af14c27b0f7
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Notify safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
