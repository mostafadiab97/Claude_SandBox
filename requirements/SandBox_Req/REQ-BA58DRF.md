---
id: REQ-BA58DRF
type: test-case
title: "Verify: Login screen validates audit records"
status: Review
priority: Medium
owner: M. Farouk
tags:
  - regulatory
  - safety
former-id: TC-X2D3JE
parent: REQ-WR5ZJN9
order: b1Q
links:
  - type: verifies
    target: REQ-RR2A2CN
    confirmed: 618b62b567a5
  - type: verifies
    target: REQ-4JBECB9
    confirmed: 2c36623fc5b2
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Store relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
