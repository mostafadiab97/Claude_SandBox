---
id: REQ-FP61N79
type: test-case
title: "Verify: Device registry authenticates sensor readings"
status: Draft
priority: Medium
tags:
  - ux
  - connectivity
former-id: TC-M1SK14
parent: REQ-8351896
order: b1Q
links:
  - type: verifies
    target: REQ-5RN3ZTR
    confirmed: 3f594322748c
  - type: verifies
    target: REQ-SMBPPQ6
    confirmed: 38ca4bb40969
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Log the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
