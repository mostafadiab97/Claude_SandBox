---
id: REQ-15HC52Q
type: test-case
title: "Verify: Heat pump driver logs safety limits"
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - power
former-id: TC-JDWV1Y
parent: REQ-XGWSK2K
order: b0t
links:
  - type: verifies
    target: REQ-JVX09VR
    confirmed: 4edc21a3fb0f
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Measure the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
