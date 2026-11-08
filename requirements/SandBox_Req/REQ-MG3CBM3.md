---
id: REQ-MG3CBM3
type: test-case
title: "Verify: User account service reports the operating mode"
status: Review
priority: Medium
owner: محمد علي
tags:
  - security
  - accessibility
former-id: TC-M60E1R
parent: REQ-8351896
order: aM
links:
  - type: verifies
    target: REQ-6PP7HZP
    confirmed: 02dd9854df79
  - type: verifies
    target: REQ-X657499
    confirmed: a9ad8edc6a5a
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Calibrate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
