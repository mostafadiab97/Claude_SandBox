---
id: TC-PH2GQ6
type: test-case
title: "Verify: Login screen restores sensor readings"
status: Review
priority: High
tags:
  - release-2.0
parent: INFO-J0FETE
order: 30
links:
  - type: verifies
    target: SYS-6REMTR
    confirmed: e73f40f41cec
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Validate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
