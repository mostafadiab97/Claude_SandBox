---
id: REQ-360T6HN
type: test-case
title: "Verify: Relay board validates energy consumption"
status: Draft
priority: Medium
owner: محمد علي
tags:
  - security
  - customer-request
former-id: TC-BZAB46
parent: REQ-F9Z1FYS
order: b1D
links:
  - type: verifies
    target: REQ-0ANDY61
    confirmed: f59e21414ac4
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Calibrate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
