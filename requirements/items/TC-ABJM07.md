---
id: TC-ABJM07
type: test-case
title: "Verify: Login screen notifys error conditions"
status: Review
priority: Medium
owner: J. Müller
parent: INFO-J0FETE
order: 220
links:
  - type: verifies
    target: SYS-61AT7T
    confirmed: 3112309b1698
  - type: verifies
    target: SW-A11K9R
    confirmed: 24ff723bc647
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Display sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
