---
id: TC-8R1HBV
type: test-case
title: "Verify: Encryption layer synchronises relay events"
status: Approved
priority: Medium
owner: É. Laurent
parent: INFO-Z4TW4B
order: 210
links:
  - type: verifies
    target: SYS-JGTNYP
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Notify relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
