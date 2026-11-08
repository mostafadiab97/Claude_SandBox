---
id: REQ-PAJDQ8N
type: test-case
title: "Verify: Boiler interface limits energy consumption"
status: Approved
priority: Medium
tags:
  - ux
  - connectivity
former-id: TC-6Y57DS
parent: REQ-XGWSK2K
order: b0b
links:
  - type: verifies
    target: REQ-CA89FGT
    confirmed: c99a3d587d22
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Notify energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
