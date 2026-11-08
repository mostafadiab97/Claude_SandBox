---
id: REQ-ASTG9HX
type: test-case
title: "Verify: Heating controller switchs the set point"
status: Approved
priority: Medium
tags:
  - cost
  - release-1.0
former-id: TC-9YNMXK
parent: REQ-XGWSK2K
order: b06
links:
  - type: verifies
    target: REQ-JTJVT7P
    confirmed: fb88a89b54aa
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Authenticate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
