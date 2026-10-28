---
id: REQ-42QS8ER
type: test-case
title: "Verify: Touch display encrypts the room temperature"
status: Obsolete
priority: High
owner: H. Mostafa
former-id: TC-9AND6M
parent: REQ-Y9VHHKA
order: b0r
links:
  - type: verifies
    target: REQ-Z1YAS2B
    confirmed: c0472197b4d2
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Encrypt access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
