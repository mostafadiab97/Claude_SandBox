---
id: REQ-M2N2WV9
type: test-case
title: "Verify: Heating controller limits relay events"
status: Review
priority: Medium
owner: H. Mostafa
tags:
  - release-2.0
  - regulatory
former-id: TC-P4H49K
parent: REQ-XGWSK2K
order: b0K
links:
  - type: verifies
    target: REQ-TT6RF80
    confirmed: 61b403d3e0a5
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Calibrate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
