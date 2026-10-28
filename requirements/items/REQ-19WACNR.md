---
id: REQ-19WACNR
type: test-case
title: "Verify: Pairing process logs firmware images"
status: Draft
priority: Medium
owner: H. Mostafa
former-id: TC-VSXW8T
parent: REQ-67RQXCK
order: b1O
links:
  - type: verifies
    target: REQ-1K6VZF7
    confirmed: 0ce16e7c9c10
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Notify the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
