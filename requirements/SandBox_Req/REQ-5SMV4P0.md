---
id: REQ-5SMV4P0
type: test-case
title: "Verify: Pairing process measures firmware images"
status: Approved
priority: Medium
owner: É. Laurent
former-id: TC-AN3CGF
parent: REQ-67RQXCK
order: aM
links:
  - type: verifies
    target: REQ-MM8GTZJ
    confirmed: 2f3dabce7169
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Store firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
