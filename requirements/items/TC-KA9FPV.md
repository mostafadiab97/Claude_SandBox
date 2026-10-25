---
id: TC-KA9FPV
type: test-case
title: "Verify: Mobile app limits humidity values"
status: Review
owner: L. Samir
parent: INFO-J0FETE
order: 390
links:
  - type: verifies
    target: SYS-G2YZ1M
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
