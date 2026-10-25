---
id: TC-CHRXKZ
type: test-case
title: "Verify: Login screen restores the connection state"
status: Review
priority: Medium
owner: S. Adel
tags:
  - regulatory
  - performance
parent: INFO-J0FETE
order: 670
links:
  - type: verifies
    target: SYS-841ZEK
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
