---
id: REQ-67FSE29
type: test-case
title: "Verify: Device registry detects sensor readings"
status: Approved
priority: Medium
former-id: TC-16STGH
parent: REQ-8351896
order: b0J
links:
  - type: verifies
    target: REQ-C3CYGWN
    confirmed: b56f90ef8f2c
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Encrypt firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
