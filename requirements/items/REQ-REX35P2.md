---
id: REQ-REX35P2
type: test-case
title: "Verify: Login screen switchs the operating mode"
status: Draft
priority: High
owner: L. Samir
tags:
  - safety
  - power
  - security
former-id: TC-HFGJMJ
parent: REQ-WR5ZJN9
order: aZ
links:
  - type: verifies
    target: REQ-670N5PW
    confirmed: f81d3e3b2c08
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
