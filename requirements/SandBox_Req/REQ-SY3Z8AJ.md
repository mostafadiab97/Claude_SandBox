---
id: REQ-SY3Z8AJ
type: test-case
title: "Verify: Login screen validates relay events"
status: Review
tags:
  - accessibility
  - safety
  - performance
former-id: TC-01BGNA
parent: REQ-WR5ZJN9
order: ap
links:
  - type: verifies
    target: REQ-P07CV0Z
    confirmed: d6dd62a6b8eb
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Store humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
