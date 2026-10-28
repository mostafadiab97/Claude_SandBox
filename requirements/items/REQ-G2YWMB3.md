---
id: REQ-G2YWMB3
type: test-case
title: "Verify: Pairing process encrypts the room temperature"
status: Draft
priority: Medium
owner: L. Samir
former-id: TC-PJKHC6
parent: REQ-67RQXCK
order: aW
links:
  - type: verifies
    target: REQ-VP326G6
    confirmed: 7ffa04910a1e
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Measure sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
