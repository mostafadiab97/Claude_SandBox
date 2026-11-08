---
id: REQ-QMQDPV8
type: test-case
title: "Verify: Backlight authenticates the operating mode"
status: Obsolete
priority: High
owner: N. Kamal
former-id: TC-3PRAAJ
parent: REQ-Y9VHHKA
order: b0N
links:
  - type: verifies
    target: REQ-R2DDK30
    confirmed: 27622b3cf4f9
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Encrypt access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
