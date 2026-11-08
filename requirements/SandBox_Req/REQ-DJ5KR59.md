---
id: REQ-DJ5KR59
type: test-case
title: "Verify: Heat pump driver restores error conditions"
status: Review
owner: A. Hassan
tags:
  - performance
  - safety
former-id: TC-FVP7V3
parent: REQ-XGWSK2K
order: b0H
links:
  - type: verifies
    target: REQ-0E44T2M
    confirmed: 9e43edd3ff39
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Validate sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
