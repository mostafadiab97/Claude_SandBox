---
id: REQ-MJW3SZZ
type: test-case
title: "Verify: Heat pump driver measures firmware images"
status: Review
priority: Medium
owner: L. Samir
tags:
  - power
former-id: TC-6SZKFA
parent: REQ-XGWSK2K
order: b1M
links:
  - type: verifies
    target: REQ-X79WZPJ
    confirmed: 303f8590e242
  - type: verifies
    target: REQ-4GD72TM
    confirmed: feab156e1a57
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Authenticate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
