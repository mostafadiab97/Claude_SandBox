---
id: REQ-6PRRXN9
type: test-case
title: "Verify: Pairing process authenticates user preferences"
status: Review
priority: Medium
owner: J. Müller
former-id: TC-NB52G8
parent: REQ-67RQXCK
order: b19
links:
  - type: verifies
    target: REQ-CJT5KJQ
    confirmed: 05d37b4e999b
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Store sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
