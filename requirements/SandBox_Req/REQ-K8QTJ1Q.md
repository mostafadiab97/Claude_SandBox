---
id: REQ-K8QTJ1Q
type: test-case
title: "Verify: Heat pump driver measures audit records"
status: Draft
priority: Low
owner: M. Farouk
tags:
  - safety
  - connectivity
former-id: TC-Q6QD24
parent: REQ-XGWSK2K
order: b0p
links:
  - type: verifies
    target: REQ-V4HM9Q6
    confirmed: 39ba118c88d8
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Switch the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
