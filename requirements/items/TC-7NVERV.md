---
id: TC-7NVERV
type: test-case
title: "Verify: Login screen detects the set point"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - performance
parent: INFO-J0FETE
order: 140
links:
  - type: verifies
    target: SYS-7BCVCV
  - type: verifies
    target: SW-DB7P83
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Switch access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
