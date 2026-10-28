---
id: REQ-E6AXZ5W
type: test-case
title: "Verify: Pairing process logs energy consumption"
status: Review
priority: Medium
owner: M. Farouk
former-id: TC-TK32YW
parent: REQ-67RQXCK
order: b1H
links:
  - type: verifies
    target: REQ-H8CB6ZQ
    confirmed: 07bbcfe4ef37
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Switch humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
