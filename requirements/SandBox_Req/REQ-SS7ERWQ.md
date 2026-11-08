---
id: REQ-SS7ERWQ
type: test-case
title: "Verify: Pairing process reports error conditions"
status: Approved
priority: Medium
owner: محمد علي
former-id: TC-P84D93
parent: REQ-67RQXCK
order: b0e
links:
  - type: verifies
    target: REQ-PCEJJ11
    confirmed: d5f9f8f2f306
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Switch relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
