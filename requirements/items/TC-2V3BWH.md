---
id: TC-2V3BWH
type: test-case
title: "Verify: Login screen switchs firmware images"
status: Obsolete
priority: Medium
owner: H. Mostafa
tags:
  - release-1.0
parent: INFO-J0FETE
order: 170
links:
  - type: verifies
    target: SYS-HC7415
  - type: verifies
    target: SW-TSMQH4
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Notify the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
