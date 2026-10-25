---
id: TC-NEZ96X
type: test-case
title: "Verify: User account service synchronises humidity values"
status: Approved
owner: N. Kamal
parent: INFO-7P4D8D
order: 150
links:
  - type: verifies
    target: SYS-J6RJYD
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Restore user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
