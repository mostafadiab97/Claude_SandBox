---
id: REQ-C4V063P
type: test-case
title: "Verify: Mobile app logs schedule entries"
status: Draft
priority: Low
owner: H. Mostafa
former-id: TC-FJCGYY
parent: REQ-WR5ZJN9
order: aN
links:
  - type: verifies
    target: REQ-09X88MA
    confirmed: f99414faf3d8
  - type: verifies
    target: REQ-86NSB1A
    confirmed: ebb6a7b1b83a
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
