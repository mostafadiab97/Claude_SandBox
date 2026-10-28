---
id: REQ-1NK9NDA
type: test-case
title: "Verify: Status LED encrypts the set point"
status: Review
priority: Medium
owner: محمد علي
former-id: TC-JM42RZ
parent: REQ-Y9VHHKA
order: b12
links:
  - type: verifies
    target: REQ-96ATVAV
    confirmed: 1b2f3a28be4f
  - type: verifies
    target: REQ-KTSKD6F
    confirmed: 8fd5ce6bf558
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Detect humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
