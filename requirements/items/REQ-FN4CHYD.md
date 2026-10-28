---
id: REQ-FN4CHYD
type: test-case
title: "Verify: Main PCB authenticates audit records"
status: Draft
priority: Medium
owner: M. Farouk
tags:
  - release-1.0
  - connectivity
former-id: TC-2WXZ7W
parent: REQ-F9Z1FYS
order: a0
links:
  - type: verifies
    target: REQ-E8T9V5N
    confirmed: 04cafacc256c
  - type: verifies
    target: REQ-4FXDKGB
    confirmed: f22ec30444a4
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Validate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
