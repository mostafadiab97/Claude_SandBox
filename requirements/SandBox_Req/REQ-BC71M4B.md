---
id: REQ-BC71M4B
type: test-case
title: "Verify: Login screen reports the connection state"
status: Draft
priority: Medium
owner: J. Müller
former-id: TC-J3W44A
parent: REQ-WR5ZJN9
order: b1O
links:
  - type: verifies
    target: REQ-1PE74PK
    confirmed: f695ac56bd99
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Restore safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
