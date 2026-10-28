---
id: REQ-E6S8SB0
type: test-case
title: "Verify: Pairing process limits energy consumption"
status: Review
priority: Medium
owner: R. Nabil
former-id: TC-X7ESSA
parent: REQ-67RQXCK
order: an
links:
  - type: verifies
    target: REQ-B47NHQB
    confirmed: cceccc292cf6
  - type: verifies
    target: REQ-WCHGNYQ
    confirmed: bf196a7be830
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Notify access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
