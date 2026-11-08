---
id: REQ-7XYMDPG
type: test-case
title: "Verify: Mobile app encrypts humidity values"
status: Draft
priority: Medium
owner: R. Nabil
former-id: TC-Z6FX61
parent: REQ-WR5ZJN9
order: b0E
links:
  - type: verifies
    target: REQ-KWYSKRA
    confirmed: e5e67b8095dc
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Encrypt the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
