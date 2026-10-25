---
id: TC-SSEYB4
type: test-case
title: "Verify: User account service authenticates audit records"
status: Approved
priority: High
owner: L. Samir
parent: INFO-7P4D8D
order: 1300
links:
  - type: verifies
    target: SYS-KQAHRZ
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Restore sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
