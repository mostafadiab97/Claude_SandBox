---
id: TC-HFGJMJ
type: test-case
title: "Verify: Login screen switchs the operating mode"
status: Draft
priority: High
owner: L. Samir
tags:
  - safety
  - power
  - security
parent: INFO-J0FETE
order: 360
links:
  - type: verifies
    target: SYS-JD8TXM
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Measure safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
