---
id: REQ-BX7N6EB
type: test-case
title: "Verify: Login screen detects the set point"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - performance
former-id: TC-7NVERV
parent: REQ-WR5ZJN9
order: aD
links:
  - type: verifies
    target: REQ-24BZH40
    confirmed: 9b16ba8d6617
  - type: verifies
    target: REQ-MYTD6AZ
    confirmed: e42463f58435
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
