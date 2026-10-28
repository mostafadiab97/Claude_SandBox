---
id: REQ-F66HP60
type: test-case
title: "Verify: Boiler interface reports relay events"
status: Review
priority: Medium
owner: M. Farouk
tags:
  - customer-request
former-id: TC-1393CG
parent: REQ-XGWSK2K
order: a5
links:
  - type: verifies
    target: REQ-8S7NCV5
    confirmed: 52eaba4960b1
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Detect firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
