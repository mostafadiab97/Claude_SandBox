---
id: REQ-KAVPPFT
type: test-case
title: "Verify: Secure boot stores humidity values"
status: Approved
priority: High
former-id: TC-E439KF
parent: REQ-K6FGAY0
order: ai
links:
  - type: verifies
    target: REQ-SP2XMBQ
    confirmed: 3a60145a886a
  - type: verifies
    target: REQ-GMVQWKK
    confirmed: 5a5e48e6f008
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Encrypt sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
