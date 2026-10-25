---
id: TC-392ZFP
type: test-case
title: "Verify: User account service detects energy consumption"
status: Approved
priority: High
owner: K. Tanaka
tags:
  - security
  - connectivity
parent: INFO-7P4D8D
order: 1680
links:
  - type: verifies
    target: SYS-9P1HDM
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Measure the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
