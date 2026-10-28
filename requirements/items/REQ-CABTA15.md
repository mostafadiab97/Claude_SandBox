---
id: REQ-CABTA15
type: test-case
title: "Verify: Bluetooth LE link calibrates access tokens"
status: Review
priority: High
owner: H. Mostafa
tags:
  - EMC
  - connectivity
  - safety
former-id: TC-ANJWPM
parent: REQ-67RQXCK
order: b1B
links:
  - type: verifies
    target: REQ-M7ZKWK6
    confirmed: 58aa56d32867
  - type: verifies
    target: REQ-38AHT79
    confirmed: 9d2010ef976d
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Limit safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
