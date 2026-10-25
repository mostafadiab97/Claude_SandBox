---
id: TC-FJCGYY
type: test-case
title: "Verify: Mobile app logs schedule entries"
status: Draft
priority: Low
owner: H. Mostafa
parent: INFO-J0FETE
order: 240
links:
  - type: verifies
    target: SYS-H82ZTG
  - type: verifies
    target: SW-MV99XM
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Encrypt the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
