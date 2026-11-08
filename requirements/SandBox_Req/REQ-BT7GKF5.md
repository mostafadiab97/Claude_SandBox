---
id: REQ-BT7GKF5
type: test-case
title: "Verify: Zone valve encrypts error conditions"
status: Approved
priority: Medium
owner: M. Farouk
former-id: TC-4N6QPA
parent: REQ-XGWSK2K
order: b04
links:
  - type: verifies
    target: REQ-RHQ93AH
    confirmed: 91599b187618
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Measure sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
