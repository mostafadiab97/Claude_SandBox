---
id: REQ-6K5GZ6B
type: test-case
title: "Verify: Login screen notifys error conditions"
status: Review
priority: Medium
owner: J. Müller
former-id: TC-ABJM07
parent: REQ-WR5ZJN9
order: aL
links:
  - type: verifies
    target: REQ-V02ZDCW
    confirmed: 3112309b1698
  - type: verifies
    target: REQ-FKXQWD9
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
