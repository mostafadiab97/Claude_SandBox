---
id: REQ-KEE2DEN
type: test-case
title: "Verify: Heat pump driver detects safety limits"
status: Review
priority: Medium
owner: J. Müller
former-id: TC-QKEPRE
parent: REQ-XGWSK2K
order: b0J
links:
  - type: verifies
    target: REQ-4B3WXK7
    confirmed: 4ce4e1f3ce2e
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Encrypt the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
