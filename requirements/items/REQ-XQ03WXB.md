---
id: TC-NGN392
type: test-case
title: "Verify: User account service measures the set point"
status: Approved
priority: Medium
parent: INFO-7P4D8D
order: 200
links:
  - type: verifies
    target: SYS-CZQB2K
    confirmed: 3322889d2361
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Switch the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
