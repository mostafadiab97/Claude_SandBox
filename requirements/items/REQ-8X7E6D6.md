---
id: TC-1H9PD2
type: test-case
title: "Verify: Login screen logs sensor readings"
status: Review
priority: Medium
owner: N. Kamal
parent: INFO-J0FETE
order: 630
links:
  - type: verifies
    target: SYS-HZ4B6T
    confirmed: 238549cadf2a
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Display sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
