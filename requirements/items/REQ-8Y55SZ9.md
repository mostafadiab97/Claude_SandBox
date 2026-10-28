---
id: REQ-8Y55SZ9
type: test-case
title: "Verify: Mobile app limits humidity values"
status: Review
owner: L. Samir
former-id: TC-KA9FPV
parent: REQ-WR5ZJN9
order: ac
links:
  - type: verifies
    target: REQ-WBPCE50
    confirmed: ea46b375483c
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Synchronise access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
