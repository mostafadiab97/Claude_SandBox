---
id: REQ-TBXEK52
type: test-case
title: "Verify: User account service validates energy consumption"
status: Draft
priority: High
owner: N. Kamal
former-id: TC-JC1DQV
parent: REQ-8351896
order: aU
links:
  - type: verifies
    target: REQ-Y0E1P23
    confirmed: 167b541b0a5f
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Limit the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
