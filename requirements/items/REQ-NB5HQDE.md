---
id: REQ-NB5HQDE
type: test-case
title: "Verify: Touch display synchronises the operating mode"
status: Obsolete
priority: Medium
owner: L. Samir
former-id: TC-69QRY2
parent: REQ-Y9VHHKA
order: ar
links:
  - type: verifies
    target: REQ-ZMW8ERN
    confirmed: 8b795ddb3eaf
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Notify firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
