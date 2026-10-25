---
id: TC-AGW6DX
type: test-case
title: "Verify: User account service encrypts the operating mode"
status: Draft
priority: High
owner: J. Müller
parent: INFO-7P4D8D
order: 890
links:
  - type: verifies
    target: SYS-N0SS0N
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Notify sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
