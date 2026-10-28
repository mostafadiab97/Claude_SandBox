---
id: REQ-JDHVTE3
type: test-case
title: "Verify: Login screen restores the connection state"
status: Review
priority: Medium
owner: S. Adel
tags:
  - regulatory
  - performance
former-id: TC-CHRXKZ
parent: REQ-WR5ZJN9
order: b04
links:
  - type: verifies
    target: REQ-2CJCCA6
    confirmed: f5675ac44211
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Calibrate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
